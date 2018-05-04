# cookiecutter-devnet-learning-lab

A cookiecutter template for creating devnet learning `labs` quickly

If you are creating an entirely new module, you may want to start here:
https://github.com/kecorbin/cookiecutter-devnet-learning-module

If you are working in an existing module, you can add an addtional lab to that
module by running the following in the `labs` folder of your existing module.

## How to use this templates

    cookiecutter https://github.com/kecorbin/cookiecutter-devnet-learning-lab



## Sample workflow

```
➜  my-awesome-learning-module cd labs
➜  labs ls
my-awesome-learning-lab
➜  labs pwd
/tmp/Projects/my-awesome-learning-module/labs
➜  labs cookiecutter gh:kecorbin/cookiecutter-devnet-learning-lab   
lab_name [my-awesome-learning-lab]: another-lab
lab_title [lab title]: another title
lab_slug [One sentence description of the learning lab.]:
author_name [John Smith]:
author_email [jsmith@company.com]:
➜  labs
➜  labs ls
another-lab             my-awesome-learning-lab
```

## Don't have cookiecutter?

    pip install cookiecutter
