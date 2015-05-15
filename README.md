# Dotnet C# code for RabbitMQ tutorials

Here you can find the C# code examples for [RabbitMQ tutorials](http://www.rabbitmq.com/getstarted.html).

To successfully use the examples you will need a running RabbitMQ server.

## Requirements

Target Framework: .NET Framework 4

### Requirements on Windows

You need the RabbitMQ dotnet client.

* "RabbitMQ.Client.dll" [RabbitMQ .NET client]
(http://www.rabbitmq.com/releases/rabbitmq-dotnet-client/v3.4.4/rabbitmq-dotnet-client-3.4.4-dotnet-3.5.zip)
* Already in the folder.

## Code

#### [Tutorial one: "Hello World!"](http://www.rabbitmq.com/tutorial-one-dotnet.html)

##### Windows

    csc /r:"RabbitMQ.Client.dll" Send.cs
    csc /r:"RabbitMQ.Client.dll" Receive.cs

    Send.exe
    Receive.exe


#### [Tutorial two: Work Queues](http://www.rabbitmq.com/tutorial-two-dotnet.html)

##### Windows

    csc /r:"RabbitMQ.Client.dll" NewTask.cs
    csc /r:"RabbitMQ.Client.dll" Worker.cs

    NewTask.exe
    Worker.exe

#### [Tutorial three: Publish/Subscribe](http://www.rabbitmq.com/tutorial-three-dotnet.html)

##### Windows

    csc /r:"RabbitMQ.Client.dll" ReceiveLogs.cs
    csc /r:"RabbitMQ.Client.dll" EmitLog.cs

    ReceiveLogs.exe
    EmitLog.exe

#### [Tutorial four: Routing](http://www.rabbitmq.com/tutorial-four-dotnet.html)

##### Windows

    csc /r:"RabbitMQ.Client.dll" ReceiveLogsDirect.cs
    csc /r:"RabbitMQ.Client.dll" EmitLogDirect.cs

    ReceiveLogsDirect.exe
    EmitLogDirect.exe

#### [Tutorial five: Topics](http://www.rabbitmq.com/tutorial-five-dotnet.html)

##### Windows

    csc /r:"RabbitMQ.Client.dll" ReceiveLogsTopic.cs
    csc /r:"RabbitMQ.Client.dll" EmitLogTopic.cs

    ReceiveLogsTopic.exe
    EmitLogTopic.exe

#### [Tutorial six: RPC](http://www.rabbitmq.com/tutorial-six-dotnet.html)

##### Windows

    csc /r:"RabbitMQ.Client.dll" RPCServer.cs
    csc /r:"RabbitMQ.Client.dll" RPCClient.cs

    RPCServer.exe
    RPCClient.exe
