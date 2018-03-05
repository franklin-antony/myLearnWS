Access this repository: http://bit.ly/aspnetcoredocker

Mount volume of current working directory {PWD} which has source code directory as below

docker run --rm -it -v ${PWD}:C:\api microsoft/dotnet:2-runtime

docker run --rm -it -v ${PWD}:C:\api microsoft/aspnetcore:2

Then 
	
	Restore dependencies
	Publish the binaries
	Run the binaries