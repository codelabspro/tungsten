# Tungsten

A todo list app made using the steps here : 

http://yawp.io/guides/tutorials/todo-list-app

## Steps

### Use maven archetype to scaffold API

mvn archetype:generate -DarchetypeGroupId=io.yawp -DarchetypeArtifactId=yawp -DarchetypeVersion=LATEST -DgroupId=tungsten -DartifactId=tungsten -Dversion=1.0-SNAPSHOT


### Use curl to create tasks
curl -H "Content-type: application/json" -X POST -d "{'test1 title': 'test1 desc'}" http://localhost:8080/api/tasks



