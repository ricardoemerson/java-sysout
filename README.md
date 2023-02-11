<p align="center">
  <br />
  <a title="Learn more about Java SysOut" href="https://github.com/ricardoemerson/java-sysout">
    <img src="https://raw.githubusercontent.com/ricardoemerson/java-sysout/master/images/cover-logo.png" alt="Java SysOut" width="256"  height="256"/>
    </a>
</p>

## Support

**Java SysOut** is an extension created for **Visual Studio Code**. If you find it useful, please consider supporting it.

<table align="center" width="60%" border="0">
  <tr>
    <td>
      <a title="PayPal" href="https://www.paypal.com/donate?hosted_button_id=X26H7L6AVMD96">
        Donate with PayPal
      </a>
    </td>
    <td>
      <a title="Mercado Pago" href="https://mpago.la/1LvP93a">
        Donate with Mercado Pago
      </a>
    </td>
  </tr>
</table>

## Java SysOut

![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/ricardo-emerson.java-sysout.svg?style=flat-square)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/ricardo-emerson.java-sysout.svg?style=flat-square)
![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/ricardo-emerson.java-sysout.svg?style=flat-square)
![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/ricardo-emerson.java-sysout.svg?style=flat-square)
[![GitHub](https://img.shields.io/github/stars/ricardoemerson/java-sysout.svg?style=flat-square)](https://github.com/ricardoemerson/java-sysout)

Easily insert and remove `System.out.println("variable: " + variable);` statement.

![](https://raw.githubusercontent.com/ricardoemerson/java-sysout/master/images/demonstration.gif)

## Usage

With selection:
* Highlight a variable (or really any text)
* Press `Ctrl+Shift+L`
* The output (on a new line) will be: `System.out.println("variable: " + variable);`

Without selection:
* Press `Ctrl+Shift+L`
* The output (on the same line) will be: `System.out.println("");`

To remove System.out.println:
* Press `Ctrl+Shift+D`
* This will delete all System.out.println statements in the current document


## Usage of Slf4j - Simple Logging Facade for Java

With selection:
* Highlight a variable (or really any text)
* Press `Cmd+Shift+L`
* The output (on a new line) will be: `log.info("variable: {}", variable);`

Without selection:
* Press `Cmd+Shift+L`
* The output (on a new line) will be: `log.info("");`


## License
[MIT License](LICENSE)
