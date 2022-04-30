# DO-Product-Card

Este es un paquete de pruebas de despliegue de NPM

### Julian Perdomo

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProducBottons } from 'jp-product-card'
```

```
 <ProductCard
        product={ product }
        initialValues={{
            count: 0,
            // maxCount: 10,
        }}
>
    {
        ({reset, count, isMaxCountReached, maxCount, increaseBy}) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProducBottons/>
            </>
        )
    }
</ProductCard>
```