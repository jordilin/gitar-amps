# GitAR-Amps - Git All Remotes Amplifiers

![GitAR-Amps](./logo.svg)

- [GitAR-Amps - Git All Remotes Amplifiers](#gitar-amps---git-all-remotes-amplifiers)
  - [List of amplifiers](#list-of-amplifiers)
    - [Open a merge request with --fetch origin --rebase origin/\<default\_upstream\_branch\>](#open-a-merge-request-with---fetch-origin---rebase-origindefault_upstream_branch)
    - [Gather all my `assigned` pull requests in a give state sorted by project](#gather-all-my-assigned-pull-requests-in-a-give-state-sorted-by-project)
  - [License](#license)

gitar amplifiers are a curated set of scripts that provide additional workflows
by combining gitar <https://github.com/jordilin/gitar> commands.

## List of amplifiers

### Open a merge request with --fetch origin --rebase origin/<default_upstream_branch>

```bash
mr --title "New merge request"
```

### Gather all my `assigned` pull requests in a give state sorted by project

```bash
./mr-all-assigned-sort-by-project opened
```

## License

This project is licensed under

- Source code: MIT license ([LICENSE](LICENSE) or
  [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT))

- GitAR-Amps logo: [Creative Commons
Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA
4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
