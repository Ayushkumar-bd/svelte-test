<script>
    import BangDBWebSDK from "@bangdb/web-sdk/svelte";
    let config = $state({
        userService: "https://testuser.bangdb.com:18080",
        // backendURL: "https://vector.bangdb.com:18080",
        // org: "R0QVJEGE2HH8",
        // agent_name: "ayush_test",
    });
</script>

<div>
    <BangDBWebSDK {config} />
</div>
