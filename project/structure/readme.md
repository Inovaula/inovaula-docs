# Inovaula

## Directory Structure

```
inovaula
│
├── backend
│   ├── api
│   ├── async
│   ├── cache
│   ├── chat
│   └── database
├── design
│   ├── icons
│   ├── images
│   ├── logos
│   └── references
├── docs
│   ├── backend
│   ├── design
│   ├── frontend
│   ├── iac
│   └── project
│       └── structure     <-- we are here!
├── frontend
│   ├── mobile
│   └── web
│       ├── client
│       ├── dashboard
│       └── landing
├── iac
│   ├── aws
│   ├── backend
│   ├── frontend
│   └── maintenance
└── meta
    ├── credentials
    ├── meetings
    ├── messages
    ├── proposals
    ├── reports
    └── requirements
```


### Generating report

On a Mac or Linux OS, run the following code in the project root directory:

```bash
# change to project root directory

export OUTPUT_PREFIX="./docs/project/structure/directory-structure"

tree -L 3 -d -o $OUTPUT_PREFIX.html -H "" --nolinks -T "Inovaula" --noreport
tree -L 3 -n -d -o $OUTPUT_PREFIX.txt --noreport
tree -L 3 -J -d -o $OUTPUT_PREFIX.json --noreport
```
