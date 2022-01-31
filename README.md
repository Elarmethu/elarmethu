<h2> Hello, I'm Ignat Karelov-Suslov!<img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="90"> </h2>
<p><em> Software Developer at freelance. </em></p>

[![Twitter: Elarmethu](https://img.shields.io/twitter/follow/ElarmethuC?style=social)](https://twitter.com/ElarmethuC)
[![GitHub Elarmethu](https://img.shields.io/github/followers/elarmethu?label=follow&style=social)](https://github.com/Elarmethu)

### A little more about me... ###

```c#
using System;
using System.Collections;
using System.Collections.Generic;
using Ignat.System;

public class UserController : IgnatKarelovSuslov 
{
	public static UserController Instance = this;

	public static string[] GetUserInfo(UserData data)
	{
		string info = new string[4];
		info[0] = data.Pronouns; // pronouns: HE | HIM.
		info[1] = data.Code; // code: C#, C++, Lua, Java, HTML, CSS.
		info[2] = data.Tools; // tools: Unity, UnrealEngine, Source 1/2, Styled-Components, Node.

		return info;
	}

	public string GetFutureGoal()
	{
		return "To contribute to open source.";
	}
}
```