Hurtle is the orchestration framework that powers all orchestration of MCN services.


<div align="center" >
<img src="https://raw.githubusercontent.com/icclab/hurtle/master/docs/figs/hurtle-logo.png" title="hurtle" width=250px>
<br/>
<img src="https://raw.githubusercontent.com/icclab/hurtle/master/docs/figs/hurtle-logo-text.png" title="hurtle" width=250px>
</div>

# hurtle?


Q: Why is it Called hurtle?

> A: Cos we like [turtles and recursion](https://en.wikipedia.org/wiki/Turtles_all_the_way_down).

Q: What is your motto?

> A: "Confusing name, simple orchestration".


# Why hurtle?

hurtle lets you:

> offer your software as a service i.e. "hurtle it!"

Hurtle lets you automate the life-cycle management of your service, from deployment of cloud resources all the way to configuration and runtime management (e.g., scaling).

**But here comes the best part: **
> hurtle has been designed since its inception to support service composition, so that you can run complex services by (recursively!) composing simple ones. Welcome to truly modular cloud service composition! Microservices anyone?

> hurtle enables service and infrastructure orchestration to easily compose, deploy, provision and manage distributed systems

Its functionality all revolves around this idea, so the service offered is also one that can be designed with the cloud in mind, based on the [cloud-native application research of the ICCLab](http://blog.zhaw.ch/icclab/category/research-approach/themes/cloud-native-applications/).

## Where From?

hurtle has two origins:

1. Mobile Cloud Networking, obviously, where in the telcom world and in particular [Network Function Virtualisation](https://en.wikipedia.org/wiki/Network_functions_virtualization) (NFV). Here hurtle has been used to offer services that have been to date executed directly on or embedded in hardware.
2. is the ICCLab's [Cloud Orchestration Initiative](http://blog.zhaw.ch/icclab/category/research-approach/themes/cloud-orchestration/)

And well, it's all powered upon another hurtle ;-)

# Overview

This repository provides documentation for hurtle and
pointers to the other repositories that make up a complete hurtle system.

hurtle consists of the following components:

- Service Manager (SM): receives requests for new tenant service instances -> [Code](https://github.com/icclab/hurtle_sm)
- Service Orchestrator (SO): manages the lifecycle of a tenant service instance -> [Sample code](https://github.com/icclab/hurtle_sample_so)
- CloudController (CC): manages and abstracts underlying resources and SOs -> [Code](https://github.com/icclab/hurtle_cc_api)

For more details, see [hurtle.it](http://hurtle.it)

# Community & Support

Report bugs and request features using [GitHub Issues](https://github.com/icclab/hurtle/issues). For additional resources, you can contact the maintainers directly. Community discussion about turtle happens in one main place:

* The *hurtle-discuss* mailing list. Once you [subscribe to the list]( https://mailman.engineering.zhaw.ch/mailman/listinfo/icclab-hurtle),
  you can send mail to the list address: [icclab-hurtle@dornbirn.zhaw.ch](mailto:icclab-hurtle@dornbirn.zhaw.ch)
  The mailing list archives are also [available on the web](https://mailman.engineering.zhaw.ch/pipermail/icclab-hurtle/).


You can follow [@hurtle_it](https://twitter.com/hurtle_it) on
Twitter for updates and of course [on the ICCLab blog](http://blog.zhaw.ch/icclab/tag/hurtle/)

## Contributing

To report bugs or request features, submit issues [here on
GitHub](https://github.com/icclab/hurtle/issues)..
If you're contributing code, make pull requests to the appropriate
repositories (see [the repo overview](./docs/reference.md)).
If you're contributing something substantial, you should first contact
developers on the [hurtle-discuss mailing list](mailto:icclab-hurtle@dornbirn.zhaw.ch)
([subscribe](https://mailman.engineering.zhaw.ch/mailman/listinfo/icclab-hurtle).

For urgent questions please contact the [maintainers](./docs/maintainers.md) directly.

Hurtle repositories follow no written Guidelines to date.

## License

hurtle is licensed under the
[Apache License version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
See the file LICENSE.

# Made by

<div align="center" >
<a href='http://blog.zhaw.ch/icclab'>
<img src="https://raw.githubusercontent.com/icclab/hurtle/master/docs/figs/icclab_logo.png" title="hurtle" width=400px>
</a>
</div>

# Supported by

<div align="center" >
<a href='http://blog.zhaw.ch/icclab'>
<img src="https://raw.githubusercontent.com/icclab/hurtle/master/docs/figs/mcn_logo.png" title="mobile cloud networking" width=400px>
</a>
</div>
