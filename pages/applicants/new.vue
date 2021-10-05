<template>
    <div>
        <b-form v-if="show">
            <b-form-group 
                id="input-group-1"
                label="Email address :"
                label-for="input-1"
                description="We'll never share your email with anyone else."
            >
                <b-form-input
                        id="input-email"
                        v-model="form.email"
                        type="email"
                        placeholder="Enter email"
                        required
                    ></b-form-input>
            </b-form-group>
        </b-form>
    </div>
</template>

<script src="~/services/pages/applicants/new.js"></script>