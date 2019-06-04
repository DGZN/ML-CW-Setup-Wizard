# mlcw-setup-wizard
> ML CW Setup Wizard

### Overview

This module is a setup wizard inspired by yeoman generators. The idea is to provide a framework for devs to polish the setup process across common platforms and architectures. 

Setup friction should be reduced to a minimum as common pain points and configuration peculiarities are identified and solved. Setup recipies (build scripts) can be written and shared for future use when encountering edge cases or tedious deployment procedures that others may encounter in the future.

# Features

**Table of Contents**

[TOCM]


## Install

```sh
git clone <repo>
yarn
```

## Usage

```
Usage

   $ node setup.js <command> <params>

   $ node setup.js <wizard|advanced>          # Uses guided setup wizard (default action if no options are set)
   $ node setup.js check <param>              # Checks specified option (default action is too check all, supported options include: all, requirements, settings, variables, access, repositories, status, errors, issues, slackbot)
   $ node setup.js list param                 # Lists <PARAM> [Recipes, Requirements, Steps, Environments, Configurations, Variables, Repositories, Supported, Recommended, Guides, Resources, Troubleshoot, Help, Contact]
   $ node setup.js task:task-name             # Begins setup at specified task
   
 Examples

   $ node setup.js                            # Begins guided setup wizard
   $ node setup.js check all                  # Checks system for required services, configurations, settings, privileges and availability 
   $ node setup.js list steps                 # Lists high level steps and associated tasks
   $ node setup.js list recipes               # Lists core and community sourced setup recipes
```
