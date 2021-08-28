node {
  stage("Discover reference build") {
    checkout scm
    discoverGitReferenceBuild defaultBranch: "main", maxCommits: 150
  }
}