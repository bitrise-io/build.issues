# Bitrise Build Issue Report template

## Description of the issue

_Please describe the issue here_


## Environment:

__Where did the issue happen?__

_If on Bitrise.io: which stack? If not on Bitrise.io: on what operating system? (Plus any other information you can share)_

__Which build Step causes the issue and which version of the step?__


## Reproducibility

- _Does a "Rebuild" help? (You can trigger a rebuild from the Build's page, by clicking the "Rebuild" button in the top right corner of a finished build)_ : YES/NO
- _Does a rebuild without caches help? (You can remove the `Cache:Pull` and `Cache:Push` steps temporarily to not to use the cache, or [you can *delete all the caches* on the `Settings` tab of the app](https://bitrise-io.github.io/devcenter/caching/about-caching/#downloading-and-deleting-caches)._ : YES/NO
- _If you have multiple different build configurations (workflows), does the issue affect all/more than one?_ : YES/NO
- _If it's an issue which happens sporadically, what's the frequency? (e.g. Once a day ; about x% of the builds)_ :
- _Does upgrading the build Step to the latest version help?_ : YES/NO
- _When did the issue start?_ :


### Linux/Android stack builds

_Can it be reproduced by running the build locally, **after doing a clean git clone (git clone the repository, into a new directory, somewhere on your Mac/PC)** and running the build from there with the Bitrise CLI ( https://www.bitrise.io/cli )? If no, can it be reproduced with Docker (using the same docker images / environment we use on bitrise.io)? Related guide: https://bitrise-io.github.io/devcenter/docker/run-your-build-locally-in-docker/ ._



### Other stacks

_Can it be reproduced by running the build locally with our CLI ( https://www.bitrise.io/cli ), **after doing a clean git clone (git clone the repository, into a new directory, somewhere on your Mac/PC)** and running the build from there with the CLI ( https://www.bitrise.io/cli )?_



## Build log

_Please attach the build log (you can download the build log from the build's page,
once the build is finished, using the "Download log" button - floating at the bottom right corner of the log viewer),
**or if you can't attach the whole log** then send the **full log** through a private channel (e.g. email - https://www.bitrise.io/contact ), **with a link to the related GitHub issue**._


