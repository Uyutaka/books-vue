<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <h1 class="mt-5">Login</h1>
                <hr>
                <form-tag>
                    <text-input label="Email" name="email" required="true" type="email">
                    </text-input>
                    <text-input label="Password" name="password" required="true" type="password"></text-input>
                    <hr>
                    <input type="submit" class="btn btn-primary" value="Login">

                </form-tag>

            </div>
        </div>
    </div>
</template>

<script>
import FormTag from './forms/FormTag.vue'
import TextInput from './forms/TextInput.vue'
export default {
    name: 'login',
    components: {
        FormTag,
        TextInput,
    },
}
</script>
