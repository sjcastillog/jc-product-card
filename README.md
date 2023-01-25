Este es un paquete de pruebas de despliegue en NPM

### JOAO CASTILLO

## Ejemplo

```
import {ProductImage, ProductCard, ProductTitle, ProductButtons } from 'jc-product-card';
```


```
<ProductCard 
    product={ product }
    initialValues={{
        count:4,
        maxCount:10
    }}
    >
        {
            ( { reset,isMaxCountReached, increaseBy, count, maxCount } )=>(<>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
                </>
            )
        }
    
</ProductCard>

```