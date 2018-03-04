Access this repository: http://bit.ly/aspnetcoredocker

Map the source code directory as below

docker run --rm -it -v ${PWD}:C:\api microsoft/dotnet:2-runtime

Then 
	
	Restore dependencies
	Publish the binaries
	Run the binaries