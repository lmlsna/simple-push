# simple-push

## Setup Envs
Load 2 the environmental variables however you want:
- `PUSHOVER_APP_TOKEN`
- `PUSHOVER_USER_KEY`

For example, include them in your `.bashrc` file:
```
export PUSHOVER_APP_TOKEN=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
export PUSHOVER_USER_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

## Arguments
Call the push scripts with the following arguments:

- `MESSAGE`   (required)
- `TITLE`     (optional)
- `URL`       (optional)
- `URL_TITLE` (optional)

## Simple Example
`./push "This is a simple notification."`

## Full Example
```
./push \
  "Required message body" \
  "My Optional Title"  \
  "https://optional.link" \
  "Link display text"
```
