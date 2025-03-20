# Consultas

## Encontrar usuario relaciones 1 a 1 integrado

```
db.usuarios.findOne({'usuario.nombre':"John Doe"})
```

## Encontrar usuario relaciones 1 a 1 con referencia de ID

```
db.usuarios.findOne({'usuario.nombre':"Jane Doe"})
```

## Encontrar usuario relaciones 1 a muchos integrado

```
db.usuarios.findOne({'autor.nombre':"John Smith"})
```

## Encontrar usuario relaciones 1 a muchos con referencia de ID

```
db.usuarios.findOne({'autor.nombre':"Jane Doe"})
```
