## file struct

what `after/plugin` at `after`
> 覆盖或追加配置：如果您想要修改由 Vim/Neovim 的内置设置或其他插件设置的选项，可以在 after 目录中创建配置文件。这些文件将在所有其他正常插件加载之后加载。
确保加载顺序：有时，插件之间的相互作用可能依赖于加载顺序。通过在 after 目录中放置配置文件，您可以确保这些设置在其他插件之后应用。
