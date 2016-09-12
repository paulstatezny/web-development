Add sections about:

 - Configuration (have default config with environment specific overrides; use environment variables to avoid saving prod config in the repo)
 - API's: REST. `include` field to optimize DB calls.
 - Code generation vs. "Abstract classes" and such
 - Passing in options to functions via option hashes (objects/associative arrays) rather than having long param lists.
 - Encapsulating common tasks via scripts and a central "script facade" (e.g. npm run ___ or Makefile)
 - Naming idiom for JavaScript event handler selector classes: `js-some-name`
 - Automate local environment setup. It should be saved in your repository -- use Vagrant or Docker or something similar so that developers simply have to install the platform and run a command (`docker-compose up -d` or `vagrant up`) and the environment will create itself. Manual environment setup is a waste of everyone's time.
 - In the same vein -- Automate deployment.
