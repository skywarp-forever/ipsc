<script>
    import {
        Navbar,
        NavBrand,
        NavLi,
        NavUl,
        NavHamburger,
        ImagePlaceholder,
        Skeleton,
        TextPlaceholder,
    } from "flowbite-svelte";
</script>

<Navbar>
    <NavBrand href="/">
        <img
            src="/images/flowbite-svelte-icon-logo.svg"
            class="mr-3 h-6 sm:h-9"
            alt="Flowbite Logo"
        />
        <span
            class="self-center whitespace-nowrap text-xl font-semibold dark:text-white"
            >IPS-C</span
        >
    </NavBrand>
    <NavHamburger />
    <NavUl>
        <NavLi href="/">Home</NavLi>
        <NavLi href="/about">IPS-C.Next</NavLi>
        <NavLi href="/docs/components/navbar">IPS-C Legacy</NavLi>
        <NavLi href="/pricing">Help</NavLi>
        <NavLi href="/contact">Login</NavLi>
    </NavUl>
</Navbar>
