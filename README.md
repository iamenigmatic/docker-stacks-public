# docker-stacks-public
### Stacking up Docker stacks.

> [!IMPORTANT]
> Almost all of these compose files share the same network.  You can call this network whatever you want, but the network needs to be created before running any of these.  If you are not familiar with doing this, the easiest way to make a new network is by using Dockhand and call it group1 so these just work as is.

> [!IMPORTANT]
> All of these use .env files when needed for secrets and you will need to provide your own details in your own file.  There may still be areas on many of these compose files that you will have to modify for yourself as well.  Read it and customize where necessary.  While you can load any of these compose files however you want, you can really step it up a level by running your own repo direct to Dockhand.  Loading in folders as stacks will load your .env files as well.  If you choose to do it by hand, make sure to place your files wherever they need to go.  I will leave discussion open on this repo and will help if I can but it won't be high priority.  Sometimes working on other people's stuff is like trying to cook in a bag of fighting cats.  You know how it is.  I like you.  We are still friends.

> [!IMPORTANT]
> While not all, many of these compose files started out from mariushosting.com.  Some of the ones you find here may match his directly and you can follow most of his guides if you find a compose here that he has a tutorial for.  This guy deserves major respect in the self hosted community and his guides are very well written.  There may be some areas in my compose that expand on what he has in a particular tutorial.  If you see a difference, use mine because it likely has added environmental variables or volumes that you will want to have, plus mine always have the same network when possible.  Combine both and have all the pleasures you desire in life.  Don't let me tell you how to live or when to brush your teeth.

## Stats
![Alt](https://repobeats.axiom.co/api/embed/ee652e89bbe32f876887026146f650fa05160024.svg "Repobeats analytics image")