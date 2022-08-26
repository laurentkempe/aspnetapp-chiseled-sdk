# Chiseled

```bash
docker build -t my/aspnetapp-chiseled .
```

```bash
docker run --rm -p 8000:8080 my/aspnetapp-chiseled
```

# Using built-in container support for the .NET SDK

https://devblogs.microsoft.com/dotnet/announcing-builtin-container-support-for-the-dotnet-sdk/

```bash
dotnet publish --os linux --arch x64 -p:PublishProfile=DefaultContainer
```


