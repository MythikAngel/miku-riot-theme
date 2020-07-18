# Miku Element Theme

An automatically updating Hatsune Miku theme for riot.im dark mode with optional square avatars.

This theme is an Element adaptation of the [Miku Discord Theme](https://github.com/MythikAngel/miku-discord-theme).

## Wallpapers
This theme uses the same background image as the Miku Discord theme. An overview with all current and past wallpapers can be found [here](https://github.com/MythikAngel/miku-discord-theme/wiki/Image-History). If the source of an image is known, it will be listed in the description. Please note that some of the images are resized or even flipped sometimes in order to make them compatible for the theme.

## Installation
First make sure the dark theme is enabled in your Riot settings (like [this](https://i.imgur.com/034bPWM.png)).

If you use the [BetterRiot extension by GeneralUltra758](https://git.nakama.tv/GeneralUltra758/better-riot) the Miku Element Theme comes bundled and automatically activated.

Or load the following code into another Riot CSS-loader:
```css
/* Miku Element Theme by MythikAngel (https://github.com/MythikAngel/miku-riot-theme) */

/* Importing CSS */
@import url("https://mythikangel.github.io/miku-riot-theme/miku.css");

/*
--|Customizing theme|--
Change these values to customize the colors and avatar-roundness of the theme.
More information and instructions can be found on the Wiki:
https://github.com/MythikAngel/miku-riot-theme/wiki/Customizing-theme
*/
:root {
	--main-color: #E20B6C;
	--hover-color: #C60962;
	--avatar-radius: 0px; /* Set to 0px for square avatars and to 50px for round avatars */
}
```
For Riot web you can use the above code with a browser CSS-injection extension like [Stylus](https://add0n.com/stylus.html).

## Customization
The accent colors and avatar radius of this theme can be customized. Take a look at the [this Wiki page](https://github.com/MythikAngel/miku-riot-theme/wiki/Customizing-theme) for instructions.

## Screenshots
#### Chat
![Chat Screenshot](https://i.imgur.com/rIJVLdF.png)

## Disclaimer
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.