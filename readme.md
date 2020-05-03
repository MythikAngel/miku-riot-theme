# Miku Riot.im Theme

An automatically updating Hatsune Miku theme for riot.im with optional square avatars.

This theme is a riot.im adoptation of the [Miku Discord Theme](https://github.com/MythikAngel/miku-discord-theme). It's in its very early stages, and is incomplete.

## Wallpapers
This theme uses the same background image as the Miku Discord theme. An overview with all current and past wallpapers can be found [here](https://github.com/MythikAngel/miku-discord-theme/wiki/Image-History). If the source of an image is known, it will be listed in the description. Please note that some of the images are resized or even flipped sometimes in order to make them compatible for the theme.

## Installation
Load the following code into a Riot CSS-loader:
```css
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
For Riot web you can use a browser CSS-injection extension like [Stylus](https://add0n.com/stylus.html).

## Customization
The accent colors and avatar radius of this theme can be customized. Take a look at the [instructions on the Miku Discord theme](https://github.com/MythikAngel/miku-discord-theme/wiki/Customizing-theme) for more information.

## Screenshots
#### Chat
![Chat Screenshot](https://i.imgur.com/8ed4bmS.png)

## Disclaimer
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.