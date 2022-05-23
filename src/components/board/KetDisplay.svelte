<script lang="ts">
    export let value: string;
</script>

<span class={value ? '' : 'ket-hidden'}>
    <span class='ket-notation'>&#8739;</span><span class='ket-value'>{value}</span><span class='ket-notation'>⟩</span>
</span>

<style lang="scss">
    .ket-hidden {
        color: rgba(0, 0, 0, 0) !important;
    }
    .ket-notation {
        opacity: 0.65;
        vertical-align: middle;
    }
    .ket-value {
        vertical-align: middle;
    }
</style>