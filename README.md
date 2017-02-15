# NuGetTemplate

This project has been moved to CodePlex (https://www.codeplex.com/). New and further updates to this project will now be posted on CodePlex at https://nugettemplate.codeplex.com/ with the documentation located at https://nugettemplate.codeplex.com/documentation

The full project structure has been included that is necessary to support the creation of a NuGet package.

You will see many folders that represent the version of .NET under the main folders: build, content, lib & Tools. For example, If you're project supports .NET 4 and above then copy your DLL to net40 under the main set of folders and above. Copying the *.pdb files with their respective DLLs will create a symbols NuGet package that allows the developers to debug your NuGet your package.

Delete folders of .NET which are not necessary for your NuGet package as they've been added for reference purpose only.

Make sure to modify the Package.nuspec file to include information about your NuGet package. An empty read me file called ReadMe.txt has also been included in the root of the project.

If you wish to submit your NuGet package to https://www.nuget.org/ then please obtain an API key and replace the key in the NuGet.config file where it's marked with the text NuGet official package source.
