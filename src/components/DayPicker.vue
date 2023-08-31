<script setup>
const props = defineProps(['calendarOptions']);
const emit = defineEmits(['selectDate']);

function handleDateSelected(event) {
  const date = new Date(event.target.value);
  emit('selectDate', date);
}
</script>


<template>
<label for="start">Date:</label>
<input
    @change="handleDateSelected" type="date" id="start" name="trip-start"
    :value="props.calendarOptions.initialDate"
    :min="props.calendarOptions.minDate"
    :max="props.calendarOptions.maxDate"
/>
</template>
