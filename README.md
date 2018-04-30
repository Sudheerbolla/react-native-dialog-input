# react-native-dialog-input
Dialog with input for React Native on iOS and Android.

## Examples

![React Native Dialog Input iOS](https://res.cloudinary.com/joseestrella/image/upload/v1525120807/dialog-ios.png)
![React Native Dialog Input Android](https://res.cloudinary.com/joseestrella/image/upload/v1525120806/dialog-android.png)

## Setup

```bash
npm install --save react-native-dialog-input
```

## Usage

```javascript
import DialogInput from 'react-native-alert-input';
...
<DialogInput isDialogVisible={this.state.isDialogVisible}
            title={"DialogInput 1"}
            message={"Message for DialogInput #1"}
            hintInput ={"HINT INPUT"}
            submitInput={ (inputText) => {this.sendInput(inputText)} }
            closeDialog={ () => {this.showDialog(false)}}>
</DialogInput>
...
```