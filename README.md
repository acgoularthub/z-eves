# Z-EVES para Linux (README em Português)

## Instalação e uso:

1. Use o comando a seguir para criar o repositório "Z" em `/opt/` e já clonar este [repositório](https://github.com/acgoularthub/z-eves.git) do git.

```bash
git clone https://github.com/acgoularthub/z-eves.git /opt/Z/
```

2. Instale os complementos "64-bits" presentes em `/opt/Z/64-bits/`, use o comando a seguir:

```bash
cd /opt/Z/64-bits/ && sudo chmod +x install.sh 
./install.sh
cd
```

3. Execute o programa com a linha a seguir:
```bash
bash /opt/Z/Z-Eves/system/z-eves-gui.sh
```

4. O programa deve iniciar uma janela GUI, use como precisar.

* Caso você pretenda, por algum motivo, executar este programa em um sistema 32-bits, ignore o "passo 2".

## Por que usar o Z-EVES?

Eu realmente desconheço outras utilidades para este programa senão para fins acadêmicos, seja estudando Engenharia de Software ou qualquer matéria relacionada a cursos como Ciência da Computação.

O propósito para o qual precisei deste programa foi para exercícios provenientes do Bacharelado em Ciência da Computação.

Esta é uma versão utilizada em Linux, a distro que uso no momento em que escrevo este README (e que funcionou) é o Ubuntu 20.04 e funcionou perfeitamente.

Este repositório é um Fork que fiz do [Arandi Lopez](https://github.com/arandilopez/z-eves), um dos poucos lugares de onde é possível encontrar este programa utilizável. Decidi traduzir e alterar o README original para ajudar futuros usuários que tenham pouca experiência em ler a documentação de softwares no github.

## Manual

Você pode utilizar este [manual](https://github.com/arandilopez/z-eves/blob/master/97-5505-04g.pdf) fornecido pelos desenvolvedores deste software para buscar por mais informações.

## Licença
Todos os direitos são reservados aos desenvolvedores do software (Provavelmente a ORA Canada).