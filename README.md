# How to Build

With Docker for Desktop installed and Balena CLI run the following command

`balena build --application <environment> --emulated`

Once built, then do...

`balena deploy pihole-dev` to push up the recently built image.

Custom Image creation

`balena preload <image_location> --app <app_id>`
