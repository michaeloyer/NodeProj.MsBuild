# NodeProj.MsBuild

Experimental repo I may turn into a nuget package. Got it working so simply including the generated nuget package in a project will `npm install` or `yarn` on the first time running `dotnet build`, do `npm run build` or `yarn build` on every `dotnet build` and reset the 'first time' install by doing a `dotnet clean`. 

More documentation to come when I get around to it, but learned a bit about MSBuild with this little experiment I thought it deserved its own repo.

Inspiration came from wanting to setup and run [Fable](https://fable.io/) with a simple `dotnet build` command. I'll probably turn my little test app into a working fable app with this package at some point.

Learned to run `npm` commands from [this blog post](https://www.meziantou.net/running-npm-tasks-when-building-a-dotnet-project.htm). Learned you could simply pull in a nuget package and have the current project use custom build targets from [CSharpier.MsBuild](https://github.com/belav/csharpier/tree/master/Src/CSharpier.MsBuild).
