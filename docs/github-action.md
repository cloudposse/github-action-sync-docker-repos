<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| dest | The destination repository to sync to. | N/A | true |
| dest-credentials | The destination repository credentials. | N/A | false |
| override-arch | Override the architecture of the src image. | N/A | false |
| override-multi-arch | If one of the images in src refers to a list of images, instead of copying just the image which matches the<br>current OS and architecture, attempt to copy all of the images in the list, and the list itself.<br> | true | false |
| override-os | Override the operating system of the src image. | N/A | false |
| src | The source repository to sync from. | N/A | true |
| src-credentials | The source repository credentials. | N/A | false |


<!-- markdownlint-restore -->
