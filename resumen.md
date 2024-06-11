MAC : message authentication code --> para integridad de mensajes 

- **PRG**: Pseudo random generator. Se usa para decir que un Adv no puede distinguir si el valor que le mandaron es random o no si ε ≈ 0. Donde ε es la diferencia entre probabilidades de los experimentos entre un número random puro o un numero de la PRG para un adversario.
- **PRF**: Lo mismo que **PRG** pero no necesita un elemento random K. Es una familia de funciones "Pseudo random family function"
- **PRP**: Pseudo random permutation family. Simlar a **PRF** pero es inversible.
- **SKES**: Secret-key encryption scheme. Cifrado simétrico.
- **Secreto perfecto**: Probabilidad de que encriptando con un SKES dos mensajes distintos te den el mismo cifrado sea la misma.
- **OTP**: One time pad. Ofrece secreto perfecto, encriptas y desencriptas haciendo un XOR con una misma clave.
- **OT ε-secrecy**: Relajas la definición de **Secreto perfecto** buscando que la diferencia entre las probabilidades de que dos mensajes distintos te den el mismo cifrado sea menos a ε.
- **IND-CPA**: (ε,t,q)-Indistinguishibility under chosen-plaintext attacks. El mismo concepto que **OT-ε** pero para multiples ataques. (NOT SURE DE ESTO)
- **PRF-CTR**: Ciframos de a pedazos del mensaje dividiendolo XOReando. Es descifrable con la key.
