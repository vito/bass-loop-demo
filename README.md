# Bass Loop demo

A demo repo for [Bass Loop], a CI/CD stack for [Bass].

To play with it, [install and set up Bass][getting-started] and start a runner:

```sh
# replace vito with your username
bass --runner vito@github.bass-lang.org
```

Next, submit a PR to this repo and Loop will run the checks defined in
[project.bass](project.bass) using your runner. To view the output, click the
"Details" link on the check and click through to the run.

[Bass Loop]: https://github.com/vito/bass-loop
[Bass]: https://github.com/vito/bass

[getting-started]: https://bass-lang.org/guide.html#getting-started
