// FormComponent.vue

<template>
    <div class="container">
        <h3 style="margin-top:30px">Simple Desktop Push Notification Example</h3>
        <form style="margin-top:30px">
            <div class="form-group">
                <label>Title:</label>
                <input type="text" class="form-control">
            </div>
            <div class="form-group">
                <label>Body:</label>
                <textarea cols="8" rows="8" class="form-control"></textarea>
            </div>
            <button class="btn btn-primary">Submit</button>
        </form>
    </div>
</template>

<script>
    export default {
    }
</script>