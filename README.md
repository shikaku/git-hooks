# Hooks for git

Add `[[ -n "$CI" || "$1" == ".git/MERGE_MSG" ]] && exit 0` before hook in order to disabled one for CI and Merge commits.
