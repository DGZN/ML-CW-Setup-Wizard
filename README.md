# mlcw-setup-wizard
> ML CW Setup Wizard

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
