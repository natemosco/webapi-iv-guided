# Deployment Notes

## Quote

> Developers get paid to deliver value, not lines of core.
>
> &mdash; A pragmatic developer

## Jargon

_"Single Responsibility Principle"_

Do one thing really well. Only one reason to change.

## Development

- extract configuration into environment variables
- setup continuous deployment from Github to Heroku.
  - commit and push to GH and the api gets updated on Heroku.

## Switching Remotes

- `git remote set-url origin <url to new empty repository on GH>`
- `git remote -v` to see where your remotes point
