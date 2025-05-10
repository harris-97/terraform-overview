# Comprehensive List of Terraform Keywords

## Core Terraform Blocks (Top-Level Keywords)

| Keyword     | Purpose                                                  |
|-------------|----------------------------------------------------------|
| provider  | Configure cloud/service providers                        |
| resource  | Define infrastructure objects                            |
| data      | Read-only reference to existing resources                |
| variable  | Define user-configurable input values                    |
| output    | Show results after execution                             |
| module    | Import reusable Terraform modules                        |
| locals    | Define internal reusable values                          |
| terraform | Set backend, required providers, Terraform version, etc. |
| required_providers | Declare required plugins for providers            |
| required_version   | Set the minimum Terraform version                |

## Within terraform Block

| Keyword     | Purpose                                |
|-------------|----------------------------------------|
| backend   | Configure remote state storage         |
| experiments | Enable experimental features         |

## Meta-Arguments (Inside Resources/Modules)

| Keyword        | Purpose                                              |
|----------------|------------------------------------------------------|
| count        | Create multiple instances of a resource              |
| for_each     | Create resources from maps or sets                   |
| depends_on   | Define explicit resource dependencies                |
| provider     | Override provider for specific resource/module       |
| lifecycle    | Control resource behavior (e.g., prevent_destroy)    |
| provisioner  | Run scripts (e.g., remote-exec, file) post-creation |
| connection   | Define how to connect to resources (for provisioners) |

## Expression Language Keywords

These aren't top-level blocks but are part of Terraform's language:

| Keyword     | Purpose                            |
|-------------|------------------------------------|
| for       | Looping (e.g., dynamic blocks)     |
| if/else | Conditionals                       |
| true/false | Booleans                        |
| null      | Represents an unset value          |
| length, join, lookup, contains, etc. | Built-in functions |

## Special Blocks (Rare / Advanced)

| Keyword         | Purpose                                         |
|------------------|-------------------------------------------------|
| dynamic        | Generate nested blocks programmatically         |
| module.<name>.*| Reference module outputs or resources           |
| output sensitive | Mark output as sensitive (e.g., for secrets)  |