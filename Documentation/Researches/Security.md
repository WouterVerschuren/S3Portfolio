# how can I add authentication to my urban Explorer webapp?

### why this research:
I want to make sure that users can have there own specific data on my website and that that they can add, update and delete this data. this will make it so that people won't be able to change data from other people. it will also for adminastrators to change or delete data when it's incorrect or unsave. It will also help with safety for the website in general. In this research I am gonna try to find a good and safe way to make sure my webapp is secured.


### What is authenticatie

authentication is a process where you determine wether a user of your website. is how they say they are. it also helps determine wether a user is real or not. authentication is often performed by having the user fill in their credidentials in the specified place on the site. Once they have done this the data will go send to the backend and the credentials that the user filled in will be compared with the credentials in the database. if the credentials are the same as the ones in the databse the user will be logged into their account. if not, then an error will accure. the reason for authentication is to have a more secure and save system.

Source: [TechTarget](https://www.techtarget.com/searchsecurity/definition/authentication)


Authenticatie is het proces waarbij iemand nagaat of een gebruiker, een andere computer of applicatie daadwerkelijk is wie hij beweert te zijn. Bij de authenticatie wordt gecontroleerd of een opgegeven bewijs van identiteit overeenkomt met echtheidskenmerken, bijvoorbeeld een in het systeem geregistreerd bewijs. De authenticiteit van het object moet worden nagegaan. Een computer met daarvoor ontworpen applicaties kan hierbij helpen.

Authentication is the second step in the access control process. The first step in this process is identification, the third and final step is authorization.

Source: [Wikipedia Authenticatie](https://nl.wikipedia.org/wiki/Authenticatie)

you can look at authentication as a lock on your door it will help keep onwanted intruders out and let trusted people. the only way you can get inside is when you have the right key and only then you will be allowed excess to your house (website).

### OAuth

OAuth (Open Authorization) is an open standard for authorization. This allows users to give a program or website access to their private data, which is stored on another website, without having to hand over their username and password. OAuth uses tokens, so that confidential data such as a username or password do not have to be provided. Each token only gives access to specific data from one website for a certain duration. For example, it can be set that a certain program only has access to the data for one year. After this, access may be requested again.

Source: [Wikipedia OAuth](https://en.wikipedia.org/wiki/OAuth)

Oauth is a commonly used structure for authorizing actors for an application or website. This autoresis makes it possible for the actors to access certain data from another app. The basic app provides the credentials (username and password of the actor) to the authentication service, which will then verify it. If these are correct, the actor receives a token that serves as a key for the other applications in order to access the correct data. The actual access is called the authorization process. This token is valid for a certain time and will therefore have to be replaced once. However, this depends on the application.


### Wat is het verschil tussen authenticatie en autorisatie

Authentication and authorization are two terms often used together, but they carry distinct meanings. Authentication involves verifying whether a user is genuine and possesses the necessary rights to access a system. It entails validating unique information known only to the user, such as passwords or biometrics. On the other hand, authorization assumes that the user's identity has already been established. It primarily focuses on determining the specific data that the user is allowed or not allowed to see. While these two concepts are interconnected and reliant on each other, it's essential to differentiate between them due to their divergent purposes.

Source: [OneLogin](https://www.onelogin.com/learn/authentication-vs-authorization#:~:text=Authentication%20and%20authorization%20are%20two,authorization%20determines%20their%20access%20rights.)


### keycloak
Keycloak is an open-source Identity and Access Management solution for modern applications and services. It provides easy security integration with minimal coding. Key features include Single Sign-On, Identity Brokering with social login support, an Admin Console for centralized management, and support for standard protocols like OpenID Connect, OAuth 2.0, and SAML. Keycloak is highly versatile and can be used in various projects to establish robust security services.

Source: Keycloak About.

Gebruikte strategie: Wat is keycloak
library

Hoe gebruik ik Keycloak op mijn applicatie
Om een authenticatie systeem op mijn applicatie te krijgen. Heb ik gebruik gemaakt van keycloak.

Om te beginnen moeten we zorgen dat we een keycloak server hebben. Deze kun je downloaden van de keycloak download pagina Voor mijn project heb ik gekozen voor de Distribution powered by WildFly versie. Na het unzippen van de server kunnen we hem starten door het open van de batch file genaamd standalone.sh.
Wanneer deze versie gestart is kunnen we naar het admin pannel gaan welke default gestart wordt op localhost:8080. Bij de eerste keer moet je eerst een admin account aanmaken.
KeycloakCreateAdmin
Bron: Keycloak Getting Started

Gebruikte strategie: Hoe gebruik ik Keycloak op mijn applicatie
workshop

Prototyping
Bronnen
Wikipedia Authenticatie
Wikipedia OAuth
Strephonsays
Keycloak About
Keycloak Getting Started
Medium, Secure react with Keycloak
