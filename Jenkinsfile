node {
  stage("Discover reference build") {
    checkout scm
    discoverGitReferenceBuild defaultBranch: env.CHANGE_TARGET ? env.CHANGE_TARGET : null, maxCommits: 0, latestBuildIfNotFound: true
  }
}
