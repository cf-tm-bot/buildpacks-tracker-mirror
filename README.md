# buildpacks-tracker-mirror
An experimental mirror of the buildpacks pivotal tracker repo

This is an experimental  repository which aims are receiving mirrored github issues for the [buildpacks pivotal tracker](https://www.pivotaltracker.com/n/projects/1042066) stories.

The goal of such mirror is to help the Cf community track progress of the CF pivotal tracker stories (currently there is no way for non project members to subscribe to story updates, see related [cf-dev thread](http://cf-dev.70369.x6.nabble.com/cf-dev-FW-issue-tracker-permissions-tt2763.html#a5014) or https://github.com/cloudfoundry/cli/issues/560#issuecomment-156846815 where CLI team PM tried to add non-team members to provide ways to check story status), by leveraging github watch features to selectively subscribe to existing mirrored stories, or up-to-come future stories.

This is mirroring is automated using https://github.com/Orange-OpenSource/pivotaltrackermirror

Apologies if as part of this POC we have accidentally and transiently:
* added extra polutting [issue mentions](https://github.com/blog/957-introducing-issue-mentions) while mirroring markdown content of pivotal stories which uses the same mention markdown syntax: you may have received undesired mentions, please ignore them with our apologies.
* added extra polutting issue cross references. We're applying various ways to cleanup this undesired pollution (by temporary disabling issues, by deleting this repo, making it private). See further analysis into https://github.com/Orange-OpenSource/pivotaltrackermirror/issues/1

Please notify of other undesired side effects by submitting issues onto  https://github.com/Orange-OpenSource/pivotaltrackermirror
