# DO-Product-Card

Este es un paquete de pruebas de despliete en NPM

### Jaime Sanchez Galvis

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons } from "do-product-card";
```

```
 <ProductCard
        product={product}
        initialValues={{
          count: 4,
          maxCount: 15,
        }}
      >
        {({ reset, count, increaseBy, maxCount, isMaxCountReached }) => (
          <>
            <ProductImage
              style={{
                boxShadow: '10px 10px 10px rgba(0,0,0,0.2)',
              }}
            />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
      </ProductCard>
```
