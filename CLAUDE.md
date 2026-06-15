# seneca-user

## About
User management plugin for the Seneca.js microservices framework.
Part of the Voxgig open source initiative.

- Official repo: https://github.com/senecajs/seneca-user
- My fork: https://github.com/luiz-justino/seneca-user
- Language: JavaScript (CommonJS)
- Default branch: master (rename to main pending)

## Checks status
- content_readme: ✅ has Voxgig mention
- exist_codeconduct: ✅ exists
- version_codeconduct: ✅ updated to 2.1
- exist_license: ✅ exists
- exist_pkgjson: ✅ exists
- exist_readme: ✅ exists
- readme_headings: ✅ updated
- test_pkgjson: ✅ has test script
- check_default: ❌ branch is master, not main
- exist_entry: checking...

## Pending tasks
- [ ] Rename default branch from master to main
- [ ] Update build.yml to use main branch

## PR workflow
1. Create fix branch from master
2. Make changes via GitHub API
3. Open PR on fork → merge
4. Open PR to senecajs/seneca-user
5. Update kanban project #6

## GitHub Project
https://github.com/users/luiz-justino/projects/6

## Notes
- build.yml CI failures on Node 12/14 are pre-existing, not caused by our changes
- todo.yml failures are expected in forks (missing secrets)
