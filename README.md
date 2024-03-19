# GitHub CODEOWNERS

## Overview

This prototype is designed to gain familiarity with GitHub's CODEOWNERS tool. 

For more detailed information on CODEOWNERS, visit [CloudAvail's own wiki article](https://cloudavail.atlassian.net/wiki/spaces/CLOUD/pages/1709572097/GitHub+CODEOWNERS) or the [official GitHub documentation](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners).


## Prototype Structure

- The `CODEOWNERS` file is located in the directory `.github/` 
- This repo, contains two directories:
    * `important_files` 
    * `not_important_files`
    


## Testing

CODEOWNERS has been configured to restrict updates to the `important_files` directory.

- You *should* be able to edit the files in `not_important_files` and merge them without any problems
- You *should not* be able to merge changes to the `important_files` directory without review/approval from @jepowers





