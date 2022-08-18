# ECR Tag

Tags an existing ECR image with a new tag.

`arn_role`: Full role to run this operation with. Must be able to read the old tag's manifest and create a new image with that manifest.
`repository`: ECR reposiory name
`existing_tag`: The existing image tag
`new_tag`: The new image tag which this plugin will create

This plugin injects a new step into your pipeline immediately after it has executed to perform this operation
