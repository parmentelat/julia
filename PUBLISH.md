# Publication

An attempt to publish the PDF outputs under github Pages

## actions

inspired by / using <https://github.com/jonhue/pubtex>

## SSH key

created a SSH keypeir using the recipe at
<https://github.com/peaceiris/actions-gh-pages#%EF%B8%8F-create-ssh-deploy-key>

## secret

the github secret is named `ACTIONS_DEPLOY_KEY`

it should be added in the organization space

although for now I am experimenting with my personal account `parmentelat`

## status

for now this build fails; let's wait for the content to settle..

## HTML

made a dumb attempt to publish the HTML outputs as well; not super nice but well..

the recipe is to run

```
make4ht types.tex -shell-escape
```

not poured into gh-pages yet