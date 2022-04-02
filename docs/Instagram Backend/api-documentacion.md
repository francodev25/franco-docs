---
sidebar_position: 1
---

# API DOCUMENTACION

 !Disclaimer => Necesito actualizar esto con el header Token

## Lista de rutas

Post
* [posts/list?user_id=4](#post-by-given-user-id)


___
### <a name="post-by-given-user-id"></a>posts/list?user_id=4
* Name:  Post By Given User ID 
* Request : `GET api/v1/posts/list?user_id=4`
* Response : `PostResource`
* Status : `200` :ok_hand:

In this example response an Array Collection with two JSONs.

:information_source: Check the App\Http\Resources\V1\PostResource

```json
{
    "data": [
        {
        "id": 2,
        "userOwner": "ashtyn35",
        "userImage": "https://i.pravatar.cc/300?img=36",
        "image": "https://images.unsplash.com/photo-1613256253373-352901921b9c?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&    h=400&ixlib=rb-1.2.1&q=80&w=400",
        "likes_count": 750,
        "description": "Rem nulla vel quis beatae necessitatibus cupiditate velit.",
        "created_at": 1647049530,
        "comments_count": 3,
        "comments": [
            {
            "id": 3,
            "userOwner": "ashtyn35",
            "body": "Recusandae sunt amet sed et eaque. Accusamus sed aut sapiente nisi autem. Et error ut rem rem iure nostrum. Delectus aut quae non nobis voluptatem impedit. Minima nam illum sed cum ut provident.",
            "created_at": 1647049531
            },
            {
            "id": 4,
            "userOwner": "winnifred.jacobson",
            "body": "Repudiandae cumque magnam in tempore est. Quia aut fuga consequatur quia praesentium perferendis. Praesentium facilis veritatis unde minus. Eveniet perferendis quis est nisi adipisci et.",
            "created_at": 1647049531
            },
            {
            "id": 5,
            "userOwner": "javier.jacobson",
            "body": "Aliquam dignissimos sed quisquam sed non similique enim sunt. Eligendi consectetur odit nostrum quia.",
            "created_at": 1647049531
            }
        ]
        },
        {
        "id": 5,
        "userOwner": "ashtyn35",
        "userImage": "https://i.pravatar.cc/300?img=36",
        "image": "https://images.unsplash.com/photo-1612583386053-87b6261ff7b0?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=400&ixlib=rb-1.2.1&q=80&w=400",
        "likes_count": 77,
        "description": "Quos harum porro et.",
        "created_at": 1647049530,
        "comments_count": 6,
        "comments": [
            {
            "id": 10,
            "userOwner": "winnifred.jacobson",
            "body": "Sit nemo repudiandae assumenda similique quam quas et natus. Aut quis nobis expedita occaecati qui. Ex error excepturi tenetur sit cupiditate autem.",
            "created_at": 1647049531
            },
            {
            "id": 11,
            "userOwner": "winnifred.jacobson",
            "body": "Inventore enim rerum adipisci praesentium molestias porro. Veritatis dicta veritatis quia delectus enim. Error et nesciunt aliquam. Ut inventore expedita omnis quae sunt accusantium.",
            "created_at": 1647049531
            },
            {
            "id": 12,
            "userOwner": "winnifred.jacobson",
            "body": "Est odio consequatur sed. Sunt vero odit officiis atque ut saepe aperiam. Dolorem consequatur laborum aliquid et voluptatem vero deleniti.",
            "created_at": 1647049531
            },
            {
            "id": 13,
            "userOwner": "ashtyn35",
            "body": "Cumque animi unde quos aspernatur vel quo delectus. Ut nam quo ab. Voluptatem ut praesentium ea.",
            "created_at": 1647049531
            },
            {
            "id": 14,
            "userOwner": "ashtyn35",
            "body": "Iste labore itaque est minus reprehenderit nisi ut. Odit iste laboriosam qui est et quas adipisci accusamus. Dolore impedit est quis quo eveniet perferendis.",
            "created_at": 1647049531
            },
            {
            "id": 15,
            "userOwner": "xemard",
            "body": "Natus nemo occaecati repudiandae non velit laudantium. Fugit rerum et quisquam possimus voluptas. Possimus dolorem non maxime temporibus et. Blanditiis et sint commodi facere ut atque.",
            "created_at": 1647049531
            }
        ]
    }
    ]
}
```

___