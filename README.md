# RLBot v5 botpack

A collection of ready-to-use bots and scripts made by the community.
The compiled bot pack can be downloaded directly from the [RLBot GUI](https://github.com/RLBot/gui).

## Submission

Everyone is welcome to submit their bot/script to the bot pack.
Bots/scripts are submodules of this repository. 

Requirements
- **Open source**: Your submission must be open source, and its repository must contain all necessary files and/or only use public dependencies.
- **bot.toml**: Your submission must have a [`bot.toml`](https://wiki.rlbot.org/v5/botmaking/config-files/#bot-script-config-files) or [`script.toml`](https://wiki.rlbot.org/v5/botmaking/config-files/#bot-script-config-files) with
	- A unique agent id. We strongly recommend the format `<yourname>/<botname>/<version>`,
	- A name,
	- A working run command (an optionally a linux run command),
	- A logo file, and
    - All fields in the details section (description, fun fact, source link, developer, language, tags).
- **bob.toml**: A properly configured `bob.toml` file which allows our tool [bob](https://github.com/swz-git/bob) to build and package the submission. See the bob repository for further instructions.
- **Skill Limit**: Your bot must be platinum rank or lower (equal to Element or lower) due to the risk of cheaters taking advantage of your bot.
- **License (optional)**: Add a [LICENSE](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository) file for your bot. The license must allow this bot pack to use the code and distribute the submission. If you do not include a LICENSE, the bot pack defaults to the [MIT license](https://license.md/licenses/mit-license/).

After checking the requirements above, make a pull request to this repository that adds your bot as a submodule using `git submodule add <yourgitrepo.git>`.

## License

The submodules in this repository are under the MIT license (see LICENSE), unless the individual submodules specify otherwise. Moreover, the owner of each submodule repository is allowed to change their license at any time as long as the new license still allows the bot pack to use the code and distribute the submission.

The owner of each submodule repository can request that their repository is removed as a submodule at any time.

## Bob

[Bob the bot builder](https://github.com/swz-git/bob) is the tool used by the botpack to build, package, and generate incremental patches for the botpack.
For this reason, your bot must have a properly configured `bob.toml` that allows Bob to build your bot.

For examples on how to use Bob, see <https://github.com/swz-git/bob-example>.
