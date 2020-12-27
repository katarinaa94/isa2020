# Vežbe 9

## Testiranje

Primer pisanja jediničnih ([unit](https://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-testing.html)) i integracionih ([integration](https://docs.spring.io/spring/docs/current/spring-framework-reference/html/integration-testing.html)) testova u Spring-u nalazi se u projektu _testing-example_.

Jedan od najpopularnijih okvira za pisanje unit testova je [Mockito](http://site.mockito.org/) koji možete koristiti i za svoje projekte.

Podrška za pisanje testova u Spring aplikacijama se može uključiti dodavanjem odgovarajućih zavisnosti u `pom.xml`:

```
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>
    
    <dependency>
        <groupId>org.mockito</groupId>
        <artifactId>mockito-core</artifactId>
    </dependency>
```

Prezentacija se nalazi na [linku](https://github.com/katarinaa94/isa2020/blob/master/isa2020/Vezbe9/Testiranje.pdf).

## Application deployment

Primer aplikacije sa uputstvom možete pronaći na [linku](https://github.com/katarinaa94/deployment-example).
