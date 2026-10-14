# ci-sandbox

Throwaway repository used to prove GitHub's runner-group workflow policy before
any product repository gets a fleet runner. It carries no product code and no
secrets. It will be deleted when the proof is recorded.

Layout: `ci.yml` is a thin caller; `pipeline.yml` and `release.yml` are the
reusable workflows the runner group allows at `refs/heads/main`.

Fork probe.
