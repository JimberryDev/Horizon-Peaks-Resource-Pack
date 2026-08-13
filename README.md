# Horizon Peaks Resource Pack

The resource pack for Horizon Peaks.

## Adding an item model

Fork the repository, add your files to the `main` resource pack, and open a pull request.

A custom item model should look roughly like this:

```text
main/assets/<namespace>/
├── items/
│   └── <item>.json
├── models/
│   └── item/
│       └── <item>.json
└── textures/
    └── item/
        └── <texture>.png
```

If you use [Blockbench](https://www.blockbench.net/) to make the custom item model, you can export it and it will automatically create the three necesary files.

## Getting the items in the server

We use [ModelApplier from ewanhowell5195](https://modrinth.com/datapack/modelapplier). To use it, you can name an item the model it should have, then open the quick actions menu which should appear in the pause menu and click on Model applier and apply item model. For more info, visit its [modrinth page](https://modrinth.com/datapack/modelapplier).
