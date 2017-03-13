# scripthookv-sdk-nuget

A nuget package for Alexander Blade's Script Hook V SDK.

## Requirements

* [Script Hook V SDK](http://www.dev-c.com/gtav/scripthookv/)
* [Nuget](https://www.nuget.org/)

## Usage

  * Extract the [Script Hook V SDK](http://www.dev-c.com/gtav/scripthookv/) into "[/sdk](/sdk)".
  * Create nuget package, and add the package to your local nuget package feed.

    ```
    nuget pack
    nuget add ScriptHookV.SDK.x.x.x.nupkg -Source <path-to-your-package-feed>
    ```

## License

All the source code is licensed under the conditions of the [MIT license](LICENSE.txt).
