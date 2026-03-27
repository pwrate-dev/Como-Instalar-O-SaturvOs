# Como-Instalar-O-SaturvOs

1. Instale O QEMU Para Rodar O .Img com mais Facilidade
2. Instale O SaturvOs.img e coloque em uma pasta separada apenas pra ele
3. Entre o No Cmd ou Terminal e Procure a Pasta Exp "Cd C:/Satv"
4. use o Codigo:
5. Após a Instalação é só ser Feliz.  Esse Tutorial Serve Pra todas Versões .img do SaturvOs, Caso Ele ja esteja em .iso quando você estiver baixando terá outro tutorial mais recente.  

 # linux /ubuntu/debian/arch(gay)
 qemu-system-i386 -drive format=raw,file=SaturvOs.img
 
 # Windows
 qemu-system-i386 -drive file=SaturvOS.img,format=raw,index=0,media=disk -machine pcspk-audiodev=snd0 -audiodev dsound,id=snd0
