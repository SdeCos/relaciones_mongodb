Tipos de relaciones mongodb:

- 1 A 1:

  - [integrado](1_a_1/integrado.json)
  - [referencia id](1_a_1/id_ref.json)

- 1 A Muchos:

  - [integrado](1_a_muchos/integrado.json)
  - [referencia id](1_a_muchos/id_ref.json)

- Archivos combinados para importar:
  - [combinados](archivos_combinados/combinado.json)

Consultas:

- db.usuarios.findOne({'usuario.nombre':"John Doe"})
- db.usuarios.findOne({'usuario.nombre':"Jane Doe"})
- db.usuarios.findOne({'autor.nombre':"John Smith"})
- db.usuarios.findOne({'autor.nombre':"Jane Doe"})
