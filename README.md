# Facebook - Clone

## RoR BootCamp - Week 3

> Note: The posts table has a foreign key (user_id) to table users

<br>

### Initial data in User and Post:

> User.all

> Post.all


![Pic 1](https://raw.githubusercontent.com/cupOJ/Facebook_Clone/feature/item/img/1.jpg)

***


### Create an entry in User and Post:
> User.create(name: "test 3", email:"t3@t.com", age:3, gender:"M")

> Post.create(title: "Title 3", description: "D3", user_id: 3)


![Pic 2](https://raw.githubusercontent.com/cupOJ/Facebook_Clone/feature/item/img/2.jpg)

***


### Update user 2:
> u2 = User.find_by(id: 2)<br>
> u2.name = "test 2 updated"<br>
> u2.save


![Pic 3](https://raw.githubusercontent.com/cupOJ/Facebook_Clone/feature/item/img/3.jpg)


***


### Update post 2:

> p2 = Post.find_by(id: 2)<br>
> p2.name = "Title 2 updated"<br>
> p2.save

![Pic 4](https://raw.githubusercontent.com/cupOJ/Facebook_Clone/feature/item/img/4.jpg)


***


### Delete post 3 then user 3:

> Post.destroy_by(id:3)<br>
> User.destroy_by(id:3)


![Pic 5](https://raw.githubusercontent.com/cupOJ/Facebook_Clone/feature/item/img/5.jpg)


