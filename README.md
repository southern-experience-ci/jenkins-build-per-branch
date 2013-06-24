
# Params

```
h: [longOpt: 'help', required: false, args: 0, argName: 'help', description: "Print usage information - gradle flag -Dhelp=true"],
j: [longOpt: 'jenkins-url', required: true, args: 1, argName: 'jenkinsUrl', description: "Jenkins URL - gradle flag -DjenkinsUrl=<jenkinsUrl>"],
u: [longOpt: 'git-url',  required: true, args: 1, argName: 'gitUrl', description: "Git Repository URL - gradle flag -DgitUrl=<gitUrl>"],
p: [longOpt: 'job-prefix', required: true, args: 1, argName: 'templateJobPrefix', description: "Template Job Prefix, - gradle flag -DtemplateJobPrefix=<jobPrefix>"],
t: [longOpt: 'template-branch', required: true, args: 1, argName:  'templateBranchName', description: "Template Branch Name - gradle flag -DtemplateBranchName=<branchName>"],
n: [longOpt: 'nested-view', required: false, args: 1, argName: 'nestedView', description: "Nested Parent View Name - gradle flag -DnestedView=<nestedView> - optional - must have Jenkins Nested View Plugin installed"],
c: [longOpt: 'print-config', required: false, args: 0, argName: 'printConfig', description:  "Check configuration - print out settings then exit - gradle flag -DprintConfig=true"],
d: [longOpt: 'dry-run', required: false, args: 0, argName: 'dryRun', description:  "Dry run, don't actually modify, create, or delete any jobs, just print out what would happen - gradle flag: -DdryRun=true"],
s: [longOpt: 'start-on-create', required: false, args: 0, argName: 'startOnCreate', description:  "When creating a new job, start it at once."],
l: [longOpt: 'latest-regex', required: false, args: 1, argName: 'latestRegex', description: "Enter Regex of branch you want to get the latest only of - gradle flag -DlatestRegex=<latestRegex"],
v: [longOpt: 'no-views', required: false, args: 0, argName: 'noViews', description: "Suppress view creation - gradle flag -DnoViews=true"],
k: [longOpt: 'no-delete', required: false, args: 0, argName: 'noDelete', description: "Do not delete (keep) branches and views - gradle flag -DnoDelete=true"],
a: [longOpt: 'enable-disabled', required: false, args: 0, argName: 'enableDisabled', description: "Even if templated used is disabled job, this will enable the jobs created from it - gradle flag -DenableDisabled=true"],
f: [longOpt: 'filter-branch-names', required: false, args:  1, argName:  'branchNameRegex', description: "Only branches matching the regex will be accepted - gradle flag: -DbranchNameRegex=<regex>"],
usr: [longOpt: 'jenkins-user',  required: false, args: 1, argName: 'jenkinsUser', description: "Jenkins username - gradle flag -DjenkinsUser=<jenkinsUser>"],
pwd: [longOpt: 'jenkins-password',  required: false, args: 1, argName: 'jenkinsPassword', description: "Jenkins password - gradle flag -DjenkinsPassword=<jenkinsPassword>"]
```   
