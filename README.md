## Info
H5P may accumulate temporary files.

This files should be cleaned up from time to time.

We recommend you to use this cron job plugin.

This cron job also refresh H5P hub list in background.

And delete H5P contents from deleted H5P page components (Only needed for ILIAS 5.2 because newer ILIAS versions supports it native :).

## Installation

First install and enable [H5P repository plugin](https://github.com/studer-raimann/H5P).

### Install H5PCron-Plugin
Start at your ILIAS root directory
```bash
mkdir -p Customizing/global/plugins/Services/Cron/CronHook
cd Customizing/global/plugins/Services/Cron/CronHook
git clone https://github.com/studer-raimann/H5PCron.git H5PCron
```
Update and activate the plugin in the ILIAS Plugin Administration

Also have a look to [H5PPageComponent](https://github.com/studer-raimann/H5PPageComponent).

### Some screenshots
Cron:
![Cron](./doc/screenshots/cron.png)

### Dependencies
* ILIAS 5.2 or ILIAS 5.3
* PHP >=5.6
* [composer](https://getcomposer.org)
* [H5P repository plugin](https://github.com/studer-raimann/H5P)

Please use it for further development!

### Adjustment suggestions
* Adjustment suggestions by pull requests on https://git.studer-raimann.ch/ILIAS/Plugins/H5PCron/tree/develop
* Adjustment suggestions which are not yet worked out in detail by Jira tasks under https://jira.studer-raimann.ch/projects/PLH5P
* Bug reports under https://jira.studer-raimann.ch/projects/PLH5P
* For external users please send an email to support-custom1@studer-raimann.ch

### Development
If you want development in this plugin you should install this plugin like follow:

Start at your ILIAS root directory
```bash
mkdir -p Customizing/global/plugins/Services/Cron/CronHook
cd Customizing/global/plugins/Services/Cron/CronHook
git clone -b develop git@git.studer-raimann.ch:ILIAS/Plugins/H5PCron.git H5PCron
```

### ILIAS Plugin SLA
Wir lieben und leben die Philosophie von Open Source Software! Die meisten unserer Entwicklungen, welche wir im Kundenauftrag oder in Eigenleistung entwickeln, stellen wir öffentlich allen Interessierten kostenlos unter https://github.com/studer-raimann zur Verfügung.

Setzen Sie eines unserer Plugins professionell ein? Sichern Sie sich mittels SLA die termingerechte Verfügbarkeit dieses Plugins auch für die kommenden ILIAS Versionen. Informieren Sie sich hierzu unter https://studer-raimann.ch/produkte/ilias-plugins/plugin-sla.

Bitte beachten Sie, dass wir nur Institutionen, welche ein SLA abschliessen Unterstützung und Release-Pflege garantieren.
