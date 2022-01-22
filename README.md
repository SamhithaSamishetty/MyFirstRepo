# MyFirstRepo
Usage
github-download can be run from the command line. It has three required flags:

-repo. The full repository name, e.g., PovertyAction/github-download.

-to. The directory in which to save the metadata. It will be created if it does not exist already.

-token. The name of a text file that contains solely a GitHub OAuth token. GitHub will supply you a token, which is a single string. You must copy it to a text file, then specify the name of that file to -token.

All together:

java -jar github-download.jar -repo PovertyAction/github-download -token token.txt -to metadata
If the name of the .jar file is not github-download.jar, use the actual filename in the command above, or rename the file as github-download.jar. If the file is not in the current working directory, you will have to specify its path.

Next, specify the metadata to download:
