# AspnetSignalRChat

Explored this [document](https://docs.microsoft.com/en-us/aspnet/signalr/overview/getting-started/tutorial-getting-started-with-signalr),
But got to know, the missing code is starting the Signal R in startup.cs file as below.

```
public class Startup
{
    public void Configuration(IAppBuilder app)
    {
        // Any connection or hub wire up and configuration should go here
        app.MapSignalR();
    }
}


