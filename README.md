# INFR3110U-Final

**Object Pool:**

I did not actually implement the object pool in the game, but if I can, I will create the queue that will be filled out by game objects we want. I will also make a dictionary because the dictionary allows me to create as many pools as we want by defining its tag and game object. So for the implementation, I need to make sure there is a new empty queue and dictionary in it. And for each pool in the list, I will fill out the entire pool by instantiating as many objects as we defined on the maximum size of the pool. And finally spawn them by activating the first object in the queue and deactivating it by putting it at the end of the queue. Therefore, we can modify the prefab of objects and how it is being located and transformed in location and rotation. Moreover, I also need the objects to be activated, so I will make a script for it.

After implementation of object pool, it can save a lot of memory.

![duckpool](https://user-images.githubusercontent.com/71342545/206280806-4dd3af9b-3e17-4ce1-8c26-c9de72ee7adf.PNG)

**Game Management System:**

I did not actually management system in the game, but if i can, I will make up an achievement system by observer design pattern. I will make the system count how long the player takes to pass the level. If they can reach it in a short period, a reward will be added to the player’s profile.
![reward](https://user-images.githubusercontent.com/71342545/206278595-4de92e62-a7e6-4e74-922c-c9538548dab8.PNG)

It will be convenient to add and more the later achievenments since the base code for achievements system is completed. The stability will increase while reusability increased.


