# imagecon2019-ecommerce-workshop

## How to run

after cloning this repo run:

```
	yarn

```

or 

```
	npm install

```


### Server

You'll need to cd into the server/ folder and from there
run server.js using node.

> easier way is to use a tool such as nodemon to run it for you.

As you will need to configure several environment params it is best to create a sh file to run with:


```

#!/usr/bin/env bash

CLD_USER="" CLD_CLOUD="" CLD_KEY="" CLD_SECRET="" DEBUG="smocker" nodemon server.js

```

Configure the following params:

1. CLD_USER - the email address of your admin cloudinary user
2. CLD_CLOUD - your cloud name
3. CLD_KEY - the API key (retrieve from cloudinary.com/console) 
3. CLD_SECRET - the API secret (retrieve from cloudinary.com/console)


### Client

from the root of this project run:

```
	yarn start
```

or

```
	npm run start

```

## Resources

[Sign Up To Cloudinary](https://cloudinary.com/signup)

* [Image Transformations](https://cloudinary.com/documentation/image_transformations)
* [Video Transformations](https://cloudinary.com/documentation/video_manipulation_and_delivery)
* [Upload Widget](https://cloudinary.com/documentation/upload_widget)
* [Media Library Widget](https://cloudinary.com/documentation/media_library_widget)
* [Product Gallery](https://cloudinary.com/documentation/product_gallery)
* [Video Player](https://cloudinary.com/documentation/cloudinary_video_player)

