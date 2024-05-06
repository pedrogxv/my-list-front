<script>
	import { KeyRound, CircleUser, LockKeyhole } from "lucide-svelte";
</script>

<div class="flex items-center justify-center min-h-screen">
    <div class="w-full max-w-md p-6 rounded-lg">
        <h2 class="text-2xl font-semibold text-center">Login</h2>
        <form class="mt-6">
            <label class="input input-bordered flex items-center gap-2">
                <CircleUser name="name" />
                <input type="text" class="grow" placeholder="Name" />
            </label>
            <label class="input input-bordered flex items-center gap-2 mt-2">
                <LockKeyhole name="password" />
                <input type="text" class="grow" placeholder="Password" />
            </label>
            <div class="mt-6">
                <button class="btn btn-primary">
                    Login
                </button>
            </div>
        </form>
    </div>
</div>