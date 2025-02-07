# Useful JavaScript Methods by Nijat Aliyev

# How to install

```bash
npm install "@developer.nijat/js-helpers"

or

yarn add "@developer.nijat/js-helpers"
```

# How to use

```jsx
import React from "react";
import { generateRandomColor } from "@developer.nijat/js-helpers";

export default function App() {
  function test() {
    const randomColor = generateRandomColor();
    console.log(randomColor);
  }
  return <>Demo Content</>;
}
```

# Dependencies

moment

# Useful Method List

### COMMON

```
getFileSize

htmlDecode

htmlEncode

getRandomNumber

uniqueNumberFromString

normalizeGraphFilterForExpress

normalizeAzPhoneNumber

normalizeAz9DigitNumber

extractNumberFromTime

calculatePercentageOfNumber

generateRandomColor

normalizeSearchParams

sumAllBetweenTwoIntegers

capitalizeFirstLetter

convertFileToUint8Array

getUniqueListByKey

toFixedWithoutRounding
```

### DATE

```
convertMillisToMinutesAndSeconds

calculateDurationWithStartDate

convertDateToMilliSeconds

convertTime12to24

convertSecondsToTime
```

### VALIDATION

```
validateEmail

validateNumber

isJsonString
```
