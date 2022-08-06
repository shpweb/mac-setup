## Install oh-my-zsh
```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Insall zsh-autosuggestions with Oh My Zsh

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

    ```sh
    vim ~/.zshrc
    ```

    ```sh
    plugins=( 
        # other plugins...
        zsh-autosuggestions
    )
    
    e.g. plugins=(git
            zsh-autosuggestions
            )
    ```

3. Start a new terminal session.


