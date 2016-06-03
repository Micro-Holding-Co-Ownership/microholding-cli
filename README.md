# microholding-cli

create and manage your microholding company from the command line interface

**Inspiration** comes from https://github.com/Micro-Holding-Cooperativism/RepPointsServer

## Usage

Install with `npm install company-cli`, then use it like:

```
microholding init # if not already in a company repository, asks for:
# * type (choose from abstract-company implementations, e.g. company-uk-ltd)
# * name (check availability)
# * leads through the implementation independent setup process and generates the companies file structure
#   * @TODO: use "puke" idea
# * breaks if process needs manual steps to be completed in between and offers:
microholding continue # instead of `company init` in a repo that has a microholding with incomplete setup process

# the `microholding init` or `microholding continue` are greyed out and `microholding run` becomes available
company run # starts a dev server with a user interface to interact with the microholding (might also offer other "run cli usage)
```


## Related Projects
* [`microholding`](https://github.com/Micro-Holding-Cooperativism/microholding) (create and manage your one-person micro holding company)
* [`microholding-cli`](https://github.com/Micro-Holding-Cooperativism/microholding-cli)(use "microholding" from the command line)

## Contributors
Please check our [roadmap](https://github.com/Micro-Holding-Cooperativism/roadmap/issues)

This project is part of [squatup](https://github.com/SquatUp/roadmap/issues/6)
