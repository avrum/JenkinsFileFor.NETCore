# Jenkins File (Groovy) For .NETCore

This project used to support some examples of jenkinsfile for pipline builds, in .NETCore.
Currently this project contains several example of using the pipeline for dotnet core

  - Pull code, Build & Run Unittest - for a specific branch
  - Pull code, Build & Run Unittest - for merging two branches

### Features In "Jenkinsfile_Build_On_Commit"
 - You should use this pipeline for every commit in a branch.
 - Clean up your workstation + checkout your branch.
 - Notifying your bitbucket server that the build stated + complete.
 - Building you .NET core solution.
 - Running all your unittest.
 - Publishing the unittest result to Jenkins.
 - Failing the build if a unittest is broken.

### Features In "Jenkinsfile_Build_On_Merge"
 - You should use this pipeline for every pull request.
 - Clean up your workstation + checkout your master brnach + merging your current branch.
 - Notifying your bitbucket server that the build stated + complete.
 - Building you .NET core solution.
 - Running all your unittest.
 - Publishing the unittest result to Jenkins.
 - Failing the build if a unittest is broken.
 - Sending email with the build status (in a defined template) to list of predefined people.


Those pipline jenkinsfile will add this pipline template to your build:

[![Example Jenkins Pipeline|Solid](https://github.com/avrum/JenkinsFileFor.NETCore/blob/master/JenkinsPipeExample.PNG)](https://github.com/avrum/JenkinsFileFor.NETCore)


<br><br>
**If you found this repository to be helpful, you can say "thank you" by clicking the "start button. Thanks :)**
[![Start Github|Solid](https://github.com/avrum/JenkinsFileFor.NETCore/blob/master/GithubClickStart.png)](https://github.com/avrum/JenkinsFileFor.NETCore)


<br><br>
**"Sharing Is Caring" Please Contact Me For Merge Requests**
### Would appriciate if other developers and dev-ops will contribute this this project.



