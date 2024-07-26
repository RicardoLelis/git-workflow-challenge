# git-workflows:

- production (real production workload)
    - hotfixes (branches that are quick fixes on production)
- production (real production workload)
- stagging (blue / green - duplicate of our production environment and if all tests pass we'll sawp it with production)
- main (main branch where we are going to merge all our features)
    - features
- qa (perform tests before merging into staging)