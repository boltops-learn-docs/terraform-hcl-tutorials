<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraform-hcl-tutorials/blob/master/2-function-analogy/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraform Introduction: Function Analogy

This is repo contains the source code for the blog post: [Terraform HCL Intro 2: Function Analogy](https://blog.boltops.com/2020/10/02/terraform-hcl-function-analogy).

## Terraform Apply

    $ terraform apply -auto-approve
    random_pet.this: Refreshing state... [id=yellow-unicorn]

    Apply complete! Resources: 0 added, 0 changed, 0 destroyed.

    Outputs:

    pet = {
      "id" = "yellow-unicorn"
      "length" = 2
      "separator" = "-"
    }
    $

## Ruby Mock

Note, the ruby mock is not going to create an actual resource. It's just to help compare Terraform to Ruby constructs.

    $ ruby main.rb
    Outputs:

    "pet" = {
      "id" = "yellow-unicorn"
      "length" = 2
      "separator" = "-"
    }
    $
