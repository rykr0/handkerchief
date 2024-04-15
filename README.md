<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">handkerchief</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#stack">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


# About the Project

Miss the old twitter? Its lightweight, liberal, 

This is a twitter clone!


![Home page](https://i.ibb.co/vBsQTZT/1-Preview.jpg)

___
# Stack:


Front-end

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

Back-end

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

___
## What's included

- [X] Rudimentary sign-in system with JWT
- [X] Tweet functionality: add, like, retweet, reply, quote, schedule, delete, send via DM, add to bookmarks
- [X] List functionality: Create, Edit, Follow, Pin, Add users
- [X] Customizable email notification settings (not scalable)
- [X] Tweet multimedia support: images (are put on a Amazon S3 bucket (can be improved)), poll, link preview, youtube video link (uses Youtube API, better to have its own embedded video player).
- [X] User functionality: follow, block, mute
- [X] Profile functionality: edit, save, 
- [X] Site has customizable color scheme (DARK MODE ftw) 
- [X] Account Settings
  - How does twitter's 

## What's not included

- [ ] Search (though, lets be real, twitter's current search functionalities really sucks, and the platform would probably be better with a 4chan-style board/search)
- [ ] User mentions ("@*")
- [ ] Tweet thread
- [ ] "Refactoring"

<p align="right">(<a href="#readme-top">back to top</a>)</p>

___
# Installation

## Prerequisites:

Install, if you do not have:

- [Install maven](https://www.baeldung.com/install-maven-on-windows-linux-mac)
- [Install java 17](https://www.oracle.com/java/technologies/javase/jdk15-archive-downloads.html)
- [Install postgres](https://www.postgresql.org/download/)
- [Install intellij IDEA](https://www.jetbrains.com/idea/)
- [Install npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
#### Also, have these accounts:

![Google](https://img.shields.io/badge/google-4285F4?style=for-the-badge&logo=google&logoColor=white)![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

### Set up java environment for spring framework:
1. In Intellij: select `settings`>`plugins`. add the Lombok plugin.
2. In Intellij: select `project structure`. select Java 17.
3. Build the project with Maven.
### Set up containers:
4. In the docker-compose file (or in Docker desktop), run the four services: `postgres`, `pgadmin`, `zipkin`, `rabbitmq` [link](https://i.ibb.co/tCCXJLk/9-Docker-Desktop.png)
### Set up DB:
5. Open http://localhost:5050/browser/ and create these databases: `user`, `tweet`, `chat`, `lists`, `notification`, `tag`, `topic`

### Set Up AWS:
6. Create a new AWS S3 bucket. Change its access from private to public.
7. Add a public access policy to the AWS S3 bucket ([doc](https://docs.aws.amazon.com/AmazonS3/latest/userguide/access-policy-language-overview.html), [github examle](https://stackoverflow.com/questions/58580042/how-to-set-public-read-only-access-on-amazon-s3-bucket#:~:text=To%20make%20objects%20publicly%20accessible%2C%20use%20a%20policy%20like%20this%3A))
8. Get AWS keys ([link](https://supsystic.com/documentation/id-secret-access-key-amazon-s3/)) and add them to the application.properties file ([link](https://i.ibb.co/zHw537K/13-key.jpg))
9. Add the bucket, access-key, and secret-key properties to the [image-service.yml config file](https://github.com/merikbest/twitter-spring-reactjs/blob/391ddc666a79057615322898ea2715f1178fdb03/config-server/src/main/resources/config/image-service.yml#L13). 

### YouTube Data API (for video embedding):
10. Go to the Google Cloud console. Generate the Youtube Data API key ([link](https://developers.google.com/youtube/v3/getting-started#before-you-start)). Add the key to the [tweet-service.yml config file](https://github.com/merikbest/twitter-spring-reactjs/blob/391ddc666a79057615322898ea2715f1178fdb03/config-server/src/main/resources/config/tweet-service.yml#L27)
11. Add a gmail account and password to the [email-service.yml config file](https://github.com/merikbest/twitter-spring-reactjs/blob/391ddc666a79057615322898ea2715f1178fdb03/config-server/src/main/resources/config/email-service.yml#L11). Note that it is better practice to use a proper IAM; this feature will be deprecated when Google accounts do not allow less secure applications [link](https://myaccount.google.com/u/2/lesssecureapps).

### NPM, run

12. Open terminal.
```
cd frontend
npm install
# or, yarn install
```
13. In Intellij, run (Spring Boot) services in this order:
    - eureka-server
    - config-server
    - api-gateway
    - user-service
    
    ... and then all other services in any order.

14. Terminal once more.
```
cd frontend
npm start
```
15. http://localhost:3000/home

    (Default) Login: user2024@gmail.com  
    (Default) Password: qwerty123

## Screenshots

#### Add tweet
![AddTweet](https://i.ibb.co/D51M0Q5/2-Add-tweet.jpg)
___
#### Add Poll
![AddTPoll](https://i.ibb.co/Dw8B0Qf/3-Add-Poll.jpg)
___
#### Reply tweet
![Reply](https://i.ibb.co/SR3qtMG/4-Reply-tweet.jpg)
___
#### Tweet image modal
![TweetImageModal](https://i.ibb.co/gZD9L6p/5-Tweet-image-modal.jpg)
___
#### Notifications
![Notifications](https://i.ibb.co/8Y8CLyj/6-Notifications.jpg)
___
#### Full Notifications
![FullNotifications](https://i.ibb.co/dKZjYCF/7-Full-Notifications.jpg)
___
#### Search
![Search](https://i.ibb.co/MCk2r0q/8-Search.jpg)
___
#### Search Videos
![SearchVideos](https://i.ibb.co/pnFN638/9-Search-Videos.jpg)
___
#### Full tweet
![FullTweet](https://i.ibb.co/SN5Z3bD/10-Full-tweet.jpg)
___
#### Liked by Modal window
![LikedByModalWindow](https://i.ibb.co/vYts3qF/11-Liked-by-Modal-window.jpg)
___
#### Following and Followers
![FollowingAndFollowers](https://i.ibb.co/BjMSzf3/12-Following-and-Followers.jpg)
___
#### Trends
![Trends](https://i.ibb.co/BfJPZ8G/13-Trends.jpg)
___
#### Bookmarks
![Bookmarks](https://i.ibb.co/crYxw7V/14-Bookmarks.jpg)
___
#### Chat
![Chat](https://i.ibb.co/PM6qZ8n/15-Chat.jpg)
___
#### Lists
![Lists](https://i.ibb.co/ftpCZj8/16-Lists.jpg)
___
#### Full List
![FullList](https://i.ibb.co/WVZrRX7/17-Full-List.jpg)
___
#### Suggested Lists
![SuggestedLists](https://i.ibb.co/rsrgqZn/18-Suggested-Lists.jpg)
___
#### Settings
![Settings](https://i.ibb.co/r3BRZnM/19-Settings.jpg)
___
#### Customization
![Customization](https://i.ibb.co/bsqWhmN/20-Profile-Customization.jpg)
___
#### Dark theme profile
![Customization](https://i.ibb.co/h1z1BCT/21-Profile-with-color-theme.jpg)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
