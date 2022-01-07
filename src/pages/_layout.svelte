<script>
    import {metatags} from '@roxi/routify'

    metatags.title = 'My Vite Svelte Routify app'
    metatags.description = 'Description coming soon...'
</script>

<svelte:head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons"/>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,600,700"/>
</svelte:head>

<slot/>
