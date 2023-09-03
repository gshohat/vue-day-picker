# Vue Day Picker

![NPM License](https://img.shields.io/npm/l/vue-day-picker)

**Lightweight** date picker component for [Vue](https://vuejs.org/) **< 5k** 😎 <br>
Emits the [date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) selected to parent component 

![date-select](https://github.com/gshohat/vue-day-picker/assets/91323932/9954d0f6-60e9-4a7b-a1c0-2843f1914d34)



## Usage

`npm i vue-day-picker`

```
<script setup>
import DayPicker from 'vue-day-picker

const calendarOptions = {
  initialDate: '2018-07-22',
  minDate: '2018-01-01',
  maxDate: '2018-12-31',
};

function handleDateSelected(date) {
  //todo
}
</script>


<template>
<DayPicker :calendar-options="calendarOptions" @select-date="handleDateSelected"/>
</template
```

## Contact
Feel free to ping me 💫
<br>
connect@giladshohat.com

[giladshohat.com](https://giladshohat.com)
