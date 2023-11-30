# calculatepower_leo.aleo

## code
```
program calculate_power.aleo {
    // The main function 'calculate_power'.
    // You can try this function by running:
    // leo run calculate_power 3u32 4u32

    transition calculate_power(base: u32, exponent: u32) -> u32 {
        return base ^ exponent;
    }
}

```

## run
```
leo run calculate_power 3u32 4u32
```
