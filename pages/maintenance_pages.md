# Maintenance Pages

Engine Yard provides a default maintenance page, but you are encouraged to customize it to your application. Further, you could even change your maintenance page on every deploy to give deploy-specific feedback (e.g. "we are doing a database upgrade, please sit tight"). 

When a rollback is performed the maintenance page used will be the one contained in the latest deploy (preventing showing users a message from a possibly several week old deploy).

## Priority
  - `public/maintenance.html.custom`
  - `public/maintenance.html.tmp`
  - `public/maintenance.html`
  - `public/system/maintenance.html.default`

## Commands

  - `ey web enable`
  - `ey web disable`
