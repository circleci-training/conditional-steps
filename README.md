# Conditional Steps

In this example, the parameters passed to a job are conditional.

The same job is run three times in the workflow:

- The first time, the *preinstall* parameter is set to `false`.
- The second time, the *preinstall* parameter is set to `true`.
- The third time, there's no parameter specified, so it uses the default of `false`.
