# open-messenger-api

## What is an Open Messenger API?
An API which acts as a gateway between social applications. Your phone service provider doesn't force you to only communicate with people who have the same provider as you. Why should your applications?

This is a service to store contact lists for user's as well as methods of sending messages to those contact's which sits outside of the applications which use them.

## As a company, how does this work?
You will have your own access key associated with your application, any messages sent via your app will be tagged with the application it was sent from. You will also have custom metadata that you can send which is specific to different forms of custom media that will be customisable within our dashboard.

There will be a series of pre defined media types that can be sent as well (images, gifs, reacts, etc).

As a consumer of messages you can choose to only show messages to user's from particular applications that have been approved or be open to data from any application on the network. We also provide options to customise this on the individual user level.

## As a user, how does this impact me?
As a user, you will no longer be confined to using a social platform simply because all your friends are using it. You can choose whatever alternative you like which integrates our api.

This should lead to increased competition and force companies to be healthier in the approach to how they build their products to serve their users.

## Why would anyone integrate the API rather than building a moat around their product?
Companies like Facebook have no incentive to be using an API like this, however, smaller companies and ones with more niche purposes for how they communicate will gain a network effect from this.

The hope is that with enough adoption, there will be a rising tide effect that will incentivise more and more people to contribute (similar to the open source code movement) and become part of the ecosystem.

## Do I need to create an account with the API as a user?
Accounts are created behind the scenes when you create an account with an application that uses our service. (We encourage companies to let user's know that parts of their data such as contact lists are stored with an external service).

The way which we associate these user's with individuals identities is through 2FA (e.g. receiving a text message) among other forms of identity verification.

## If I don't have an account with the API provider, how do I delete my data?
The API provides endpoints for each application to be able to delete "their" data that is associated with the user. Once all data is deleted from all of the applications which the user is using, the account will be deleted automatically.

On top of this, user's can request with us directly to delete their data and we will do that for them.

## Does my data have to be stored within the API?
I think for MVP it makes the most sense, but in the long run it would be good to allow user's to have their own buckets (similar to dropbox) which they can select a provider to store their information and then my API communicates with that layer.
