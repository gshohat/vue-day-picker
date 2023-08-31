# Vue Day Picker

![NPM License](https://img.shields.io/npm/l/vue-day-picker)

**Lightweight** date picker component for [Vue](https://vuejs.org/) **< 5k** 😎 <br>
Emits the [date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) selected to parent component 

![play](https://github-production-user-asset-6210df.s3.amazonaws.com/91323932/264693995-06a66289-c670-4ae4-b37b-fa5864df86e4.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20230831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230831T152120Z&X-Amz-Expires=300&X-Amz-Signature=9e74e9d832158f29fc0230398f0a62593b564eb237f000c543a6bd86a6dd8082&X-Amz-SignedHeaders=host&actor_id=91323932&key_id=0&repo_id=685555638)

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
