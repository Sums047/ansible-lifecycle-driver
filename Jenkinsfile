#!/usr/bin/env groovy

String tarquinBranch = "TNC/tnc-o-tracking#7370"

library "tarquin@$tarquinBranch"

pipelinePy {
  pkgInfoPath = 'ansibledriver/pkg_info.json'
  applicationName = 'ansible-lifecycle-driver'
  releaseArtifactsPath = 'release-artifacts'
  attachDocsToRelease = true
  attachHelmToRelease = true
}
