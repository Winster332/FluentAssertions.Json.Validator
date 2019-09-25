# FluentAssertions.Json.Validator

[![Build Status](https://travis-ci.com/Winster332/FluentAssertions.Json.Validator.svg?branch=master)](https://travis-ci.com/Winster332/FluentAssertions.Json.Validator)

Validation json for xUnit with FluentAssertions and Newtonsoft.Json

## NuGet

[Nuget link](https://www.nuget.org/packages/FluentAssertions.Json.Validator/1.0.0)

```powershell
PS> Install-Package FluentAssertions.Json.Validator -Version 1.0.0
```

## Usage

```C#
json.Should().ContainsJson($@"
{{
  'name': '{name}',
  'age': {age}
}}");
```

LICENCE
-------
[GNU General Public License v3.0](https://github.com/Winster332/FluentAssertions.Json.Validator/blob/master/LICENSE)
