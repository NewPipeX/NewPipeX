### Fork Info
Please note that this project is **a fork** of `polymorphicshade`'s popular [NewPipe fork](https://github.com/polymorphicshade/NewPipe) which originally integrated [SponsorBlock](https://sponsor.ajay.app/) and [Return YouTube Dislike](https://returnyoutubedislike.com/) functionality, which, unfortunately, was archived and is no longer maintained (as of December 29, 2023).

This project picks up from where the previous one left off. It is being actively maintained to ensure it is kept up-to-date with upstream `NewPipe` and fully incorporates the latest changes found in each new upstream release of `NewPipe`.

Our app is designed to be a plug-and-play replacement for its discontinued parent. If there is any data you wish to migrate from your current app, [follow the guide here on how to export/import data](https://newpipe.net/FAQ/tutorials/import-export-data/#export-database).
___
# NewPipe x SponsorBlock x Return YouTube Dislike
[![Release](https://img.shields.io/github/v/release/javulticat/NewPipe?label=Release)](https://github.com/javulticat/NewPipe/releases/latest)
[![License](https://img.shields.io/github/license/javulticat/NewPipe?color=blue&label=License)](https://www.gnu.org/licenses/gpl-3.0)
[![CI](https://github.com/javulticat/NewPipe/actions/workflows/ci.yml/badge.svg?branch=sponsorblock)](https://github.com/javulticat/NewPipe/actions?query=branch%3Asponsorblock)
___
A fork of [NewPipe](https://github.com/TeamNewPipe/NewPipe) with [SponsorBlock](https://sponsor.ajay.app/) and [Return YouTube Dislike](https://returnyoutubedislike.com/) functionality.

![01](.github/images/preview01.gif)
![02](.github/images/preview02.gif)

## How can I get this?

### For versions prior to `v0.26.0`
Currently, a couple of `polymorphicshade`'s original builds are still available via `IzzyOnDroid`:
[<img alt="Get it on IzzyOnDroid" height="80" src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png">](https://apt.izzysoft.de/fdroid/index/apk/org.polymorphicshade.newpipe)

### For versions after `v0.26.0`
New builds will be uploaded in the [Releases](https://github.com/javulticat/NewPipe/releases) section. Please download the APK from the newest release and install it on your device.

_F-Droid availability is [coming soon](https://github.com/users/javulticat/projects/2)._

## Why isn't this in upstream NewPipe?
[The developer team](https://github.com/TeamNewPipe) behind the official NewPipe decided that they do not want to include these kinds of functionality in their app. See https://newpipe.schabi.org/blog/pinned/newpipe-and-online-advertising/, https://github.com/TeamNewPipe/NewPipe/pull/3205, and https://github.com/TeamNewPipe/NewPipe/issues/7469 for more information and discussion.

## Bugs

If you encounter a bug while using this fork, please only [create a bug report in this repo](https://github.com/javulticat/NewPipe/issues/new?assignees=&labels=bug%2Cneeds+triage&projects=&template=bug_report.yml) after you have confirmed that:

1. It is _not_ [a known issue with upstream `NewPipe`](https://github.com/TeamNewPipe/NewPipe/issues?q=is%3Aissue+is%3Aopen+label%3Abug).
2. You are _not_ able to recreate the bug while using upstream `NewPipe`.
   * If you find that you can, please report the bug to the upstream developers.

## Feature Requests

Please only [open a feature request in this repo](https://github.com/javulticat/NewPipe/issues/new?assignees=&labels=feature+request%2Cneeds+triage&projects=&template=feature_request.yml) if it meets one of the following criteria:

* The feature request relates to fork-specific functionality that does not exist upstream (e.g., `SponsorBlock`, `Return YouTube Dislike`)
* The feature request has already been opened upstream, _and_ it has been declined

**Please note that changes to app functionality will not be made lightly.** Only feature requests that can attract significant community support are likely to be considered for acceptance.
