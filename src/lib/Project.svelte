<script>
export let link = ''
export let text = ''
</script>

<a href="{link}"><p>{text}</p></a>

<style>
p {
    display: none;
    margin-block: 10px;
    color: #000;
}
a {
    width: 100%;
    max-width: 300px;
    height: 200px;
    border: 3px solid #000;
    border-radius: 10px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
    text-decoration: none;
}
a:hover p {
    display: block;
}
</style>