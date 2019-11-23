# ϩⲟⲩⲣⲁⲧⲉ

/hɔwratɛ/, Sadhidic Coptic for *guardians*.

## A distributed uptime notification system

There are certainly many tools to identify uptime of systems out there, although I'd prefer one that worked completely in house and was pretty minimal, but smart.
Additionally, I want to learn about consensus protocols and gRPC, so this seemed to make a good deal of sense for a little project.

---

The aim is simple: a microservice that runs on all of my VPS's, my NAS and any other machines in my network (some of which are acceptable to be down at any point in time, but can be a part of the collective when up).
Everyone knows who should be awake and when, if that isn't the case, make sure everyone agrees and send me a notification.
If there is no consensus, then attempt to trace any connectivity issue and alert me of what is known.
