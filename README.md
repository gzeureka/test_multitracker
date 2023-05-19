# test_multitracker
## Init panorama project
In `test_multitracker` dir, run:

`panorama-cli init-project --name multitracker`

## Create application package
In `test_multitracker/multitracker` dir, run:

`panorama-cli create-package --name multitracker_app`

## Create model package
In `test_multitracker/multitracker` dir, run:

`panorama-cli create-package --name multitracker_model --type Model`

## Add panorama camera package
In `test_multitracker/multitracker` dir, run:

`panorama-cli add-panorama-package --type camera --name my_camera`
