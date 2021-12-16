# Minimal Terraform module test using Terratest

Many organizations request Infrastructure automation and Infrastructure testing. Terraform is perfect for Infrastructure automation. Infrastructure testing isn't built into Terraform. Hence, additional tools are used to validate the infrastructure is deployable and functional.

This repository shows how to use Terratest to validate that your Terraform module is deployable. This might sound like a useless test, but it prevented me from pushing bad modules (modules that don't deploy) many times already. So, let's get to it!

