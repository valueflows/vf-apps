# vf-apps
Overview repo for other repos for apps based on the VF model and vocabulary.

The [Open Cooperative Ecosystem](https://docs.opencoopecosystem.net/) intends to create flocks of modular apps that will all work together using the VF vocabulary and a decentralized protocol such as [ActivityPub](https://www.w3.org/TR/activitypub/), [Scuttlebutt](https://www.scuttlebutt.nz/), or [Holochain](https://holochain.org/).

We would like the apps to be able to work on any of those three protocols and many others to come. 

Some work is already underway in each of those protocols. The one that is closest to deployment might be [Moinho-Mesh](https://viewer.scuttlebot.io/%25d2dJqZwk52zSV3z9oB5MlisgUlQGK8tFXEOn6fKf8sY%3D.sha256) in Moinho, Brazil. Their repos are currently in [the Open App Ecosystem github group](https://github.com/open-app). They first announced in the [Open App Ecosystem Loomio group](https://www.loomio.org/d/KEcf2u84/experimentation-with-open-app-ecosystem).

@bhaugen and @fosterlynn will be writing specs for a suite of apps for federated economic networks in the days to come, in separate repos in the [valueflows organization](https://github.com/valueflows). We will add links for each of those repos to this overview readme as they are published.

We will mine existing apps using VF-compatible models for ideas and logic. Those include:
* the [Vocabulator](https://github.com/valueflows/django-vocabulator)
* [Resourceful](https://github.com/valueflows/resourceful)
* [linked-data-browser](https://github.com/valueflows/linked-data-browser)
* [Holodex](https://github.com/holodex/holodex)
* The original [NRP](https://github.com/valnet/valuenetwork) developed with Sensorica.
* [OCP](https://github.com/FreedomCoop/valuenetwork) fork of NRP for FairCoop
* [Agent](https://github.com/opencooperativeecosystem/agent), first app that is truly part of OCE
* [OCE repos](https://github.com/opencooperativeecosystem)
* [LearnDeep](https://github.com/LearnDeepMilwaukee) fork of NRP + Agent
* [Sensorica's new fork of NRP for Verdun](https://github.com/Sensorica/VerdunNRP)

## The Apps

These are meant to be requirements, specifications, and ideas for apps, where different people could implement different software that fills the requirements for each app in the flock. But any implementation of any of the apps should be able to work with any other implementation of any of the other apps.

* The central apps will be **[the Agent apps](https://github.com/valueflows/vf-apps-agents)**. All the other apps in the flock will be used by the agents.
* For example: [Recipes](https://github.com/valueflows/vf-apps-recipes) and [Planning](https://github.com/valueflows/vf-apps-planning).
* **[Traversing the value flows](https://github.com/valueflows/vf-apps-traversing-the-flows).** This is not really an app, but an algorithm that can be made into a module potentially usable by many apps.
