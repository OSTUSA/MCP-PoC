# C# To TS With Copilot
This is a demo on how to use the copilot agent mode functionality in VSC to convert C# models to TS models.

This solution requires both repos to be opened in the same VSC window so copilot can access them.

Here is the promp I used:
> Generate TS models in the UI > src > app > models folder for all C# models in the API > Models folder.
> The generated TS files should use kebob-case instead of PascalCase for their file names.
> The file bodies should convert the C# model with the TypeScript equivalent.
> Use camelCase for properties and convert types like int → number, string → string, List<string> → string[], DateTime → Date, etc.
> In case of inheritance, use the extends keyword in TypeScript.
> Any custom types/classes used within the model should be imported from relevant TS files.
> Do not leave any C# code or comments in the generated TS files, only provide the TypeScript class.

Below is a demo of this approach (no audio):

<video controls>
  <source src="./CSToTSDemo.mp4" type="video/mp4">
  Your browser does not support the video tag. You can watch [here](./CSToTSDemo.mp44)
</video>
