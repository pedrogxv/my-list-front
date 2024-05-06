<script>
    import { Mail, Lock, Contact, Phone, Image, CircleUser } from 'lucide-svelte';
</script>

<main class="flex items-center justify-center w-full">
    <div class="rounded px-8 pt-6 pb-8 mb-4">
        <div class="mb-4">
            <label class="input input-bordered flex items-center gap-2">
                <CircleUser name="name" />
                <input type="text" class="grow" placeholder="Name" />
            </label>
        </div>
        <div class="mb-4">
            <label class="input input-bordered flex items-center gap-2">
                <Mail name="email" />
                <input type="text" class="grow" placeholder="Email" />
            </label>
        </div>
        <div class="mb-4">
            <label class="input input-bordered flex items-center gap-2">
                <Lock name="password" />
                <input type="text" class="grow" placeholder="Password" />
            </label>
        </div>
        <div class="mb-4">
            <label class="input input-bordered flex items-center gap-2">
                <Contact name="cpf" />
                <input type="text" class="grow" placeholder="CPF" />
            </label>
        </div>
        <div class="mb-4">
            <label class="input input-bordered flex items-center gap-2">
                <Phone name="telephone" />
                <input type="text" class="grow" placeholder="Telefone" />
            </label>
        </div>
        <div class="mb-4">
            <label class="input input-bordered flex items-center gap-2">
                <Image name="telephone" />
                <input type="text" class="grow" placeholder="Telefone" />
            </label>
        </div>
        <div class="flex items-center justify-between">
            <button
                class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline"
                type="button"
            >
                Sign In
            </button>
            <a
                class="inline-block align-baseline font-bold text-sm text-blue-500 hover:text-blue-800"
                href="#"
            >
                Forgot Password?
            </a>
        </div>
    </div>
</main>