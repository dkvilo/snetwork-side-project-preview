
# Social Network Side Project

```md
  
  The Project was developed using following technologies:
    
    - Go        (Image Processing Service: Resize, Blur, Delete, and Host)
    - NodeJs    (Apollo GraphQL Server)
    - NextJs    (Apollo GraphQL Client)
    - MongoDB   (Primary Database)
    - Redis     (Jobs, JWT Blacklisting)
    - Varnish   (Http Cashing)
    - NGINX     (Reverse Proxy, Layer 7 Load balancer (round robin))
    - Docker    (Virtualization)

  Deployed on Single instance DigitalOcean droplet with 1GB of RAM and 25GB storage,
  Also, I had increase the SWAP up to 2GB.

```

## Architecture
![alt text](images/structure.png "Architecture")




## Welcome Page
![alt text](images/welcome_page.png "Welcome Auth")
![alt text](images/welcome_page_registration.png "Welcome Register")

## Personalized Feed
![alt text](images/feed.png "Feed")
![alt text](images/feed_01.png "Feed 2")
![alt text](images/dark_mode.png "Feed 3 Dark Mode")

## Post Shallow Render (CSR) and Actions
![alt text](images/post_shallow.png "Post Shallow")
![alt text](images/post_shallow_reply.png "Post Shallow Reply")
![alt text](images/post_shallow_replied.png "Post Shallow Replied")

## Post Detail Render (SSR)
![alt text](images/post_detail.png "Post detail")
![alt text](images/post_detail_comments.png "Post detail comments")
![alt text](images/post_detail_comments_pag.png "Post detail comments pag")

## Post Card And Actions
![alt text](images/post_card_1i.png "Post Card With one image")
![alt text](images/post_card_2i.png "Post Card With two image")
![alt text](images/post_card_3i.png "Post Card With three image")
![alt text](images/post_card_4i.png "Post Card With four image")
![alt text](images/post_card_actions_owner.png "Post Card With owner actions")
![alt text](images/post_card_actions_user.png "Post Card With user actions")


## User Profile
![alt text](images/active_user_profile.png "User Profile owner")
![alt text](images/user_profile.png "User Profile")
![alt text](images/user_profile_guest.png "User Profile Non Auth")

## Traveler Mode
![alt text](images/traveler_mode_feed.png "Traveler Mode Feed")
![alt text](images/traveler_mode_feed_selected_target.png "Traveler Mode Feed Selected Location")
![alt text](images/traveler_mode_ask_question.png "Traveler Mode Feed Ask Question About Location")

