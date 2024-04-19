# jwt


# Queries

Al ejecutar el proyecto por primera vez, inserta esta querie para crear dos usuarios
INSERT INTO userinfo (username, password, name, roles, nonLocked) VALUES (
                                                                   'user@gmail.com',
                                                                   '$2a$10$h3dMLoHm2DG/aGUFEyG/0.JfKSo4sZKFA5BEA6pju..8RgFhFY5L.',
                                                                   'usuario',
                                                                   'ROLE_USER',
                                                                   true
                                                                  )
INSERT INTO userinfo (username, password, name, roles, nonLocked) VALUES (
                                                                   'admin@gmail.com',
                                                                   '$2a$10$h3dMLoHm2DG/aGUFEyG/0.JfKSo4sZKFA5BEA6pju..8RgFhFY5L.',
                                                                   'administrador',
                                                                   'ROLE_ADMIN',
                                                                   true
                                                                  )
las contraseñas de ambos son root
