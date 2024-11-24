# Fran

### todo
---

Comando para añadir un usuario AD
```cmd
New-ADUser -Name "username" -SamAccountName "samaccountname" -Path "OU=Users,DC=domain,DC=com" -AccountPassword (ConvertTo-SecureString "password" -AsPlainText -Force) -Enabled $true
```

- [ ] Configuracion del windows server ` Adaptador de Red ` ` Nombre ` ` Ping ` ` Fecha Hora `
- [ ] Instalar ` Active Directory `
- [ ] Crear usuario ` AD `
- [ ] Cambiar domain ` AD `
- [ ] Server DHCP
- [ ] Server DNS
