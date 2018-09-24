# pmk2

Create a new repository on the command line
echo "# pmk2" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/watchara510/pmk2.git
git push -u origin master

# test
command
test 222
test2 3333

# Git Credential Manager for Windows 
[![GitHub Release](https://img.shields.io/github/release/microsoft/git-credential-manager-for-windows.svg?style=flat-square)](https://github.com/Microsoft/Git-Credential-Manager-for-Windows/releases)
[![Build status](https://img.shields.io/appveyor/ci/whoisj/git-credential-manager-for-windows.svg?style=flat-square)](https://ci.appveyor.com/project/whoisj/git-credential-manager-for-windows/branch/master)
[![Coverity Scan Build Status](https://img.shields.io/coverity/scan/11371.svg?style=flat-square)](https://scan.coverity.com/projects/git-credential-manager-for-windows)
[![GitHub Downloads](https://img.shields.io/github/downloads/Microsoft/Git-Credential-Manager-for-Windows/total.svg?style=flat-square)](https://github.com/Microsoft/Git-Credential-Manager-for-Windows/releases)
[![@MicrosoftGit on Twitter](https://img.shields.io/twitter/follow/microsoftgit.svg?style=social&label=Follow%20%40microsoftgit)](https://twitter.com/microsoftgit)

* * *

## NOTICE: Experiencing GitHub push/fetch problems?

As of 22 Feb 2018, [GitHub has disabled support for weak encryption](https://githubengineering.com/crypto-deprecation-notice/) which means many users will suddenly find themselves unable to authenticate using a Git for Windows which (impacts versions older than v2.16.0). **DO NOT PANIC**, there's a fix. [Update Git for Windows](https://github.com/git-for-windows/git/releases) to the latest (or at least v2.16.0).

The most common error users see looks like:

```text
fatal: HttpRequestException encountered.
   An error occurred while sending the request.
fatal: HttpRequestException encountered.
   An error occurred while sending the request.
Username for 'https://github.com':
```

If, after updating Git for Windows, you are still having problems authenticating with GitHub, please read this [Developer Community](https://developercommunity.visualstudio.com/content/problem/201457/unable-to-connect-to-github-due-to-tls-12-only-cha.html) topic which contains additional remedial actions you can take to resolve the problem.

If you are experiencing issue when using **Visual Studio**, please read **[Unable to connect to GitHub with Visual Studio](https://developercommunity.visualstudio.com/content/problem/201457/unable-to-connect-to-github-due-to-tls-12-only-cha.html)**.

* * *
