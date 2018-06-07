node {
   checkout scm
   sh 'npm install'
   final b = nxBuildContext(projectName: 'testProject', branchName: 'master', base: "origin/master~1", head: "origin/master")
   nxBuildAffected b
   nxPostToConsole buildContext: b;
}
