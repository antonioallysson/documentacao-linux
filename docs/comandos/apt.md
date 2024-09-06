# APT (Advanced Package Tool)

O comando `apt` é uma ferramenta utilizada em sistemas operacionais baseados em Debian, como Ubuntu, para gerenciar pacotes de software. Ele permite instalar, atualizar, remover e buscar pacotes de software a partir dos repositórios oficiais do sistema ou de fontes configuradas.

## 1. Atualização de Repostiórios
- `apt update`: Este comando atualiza a lista de pacotes disponíveis nos repositórios configurados no sistema. Ele sincroniza o índice local de pacotes com os repositórios remotos, garantindo que o sistema tenha informações atualizadas sobre as versões mais recentes dos pacotes.

## 2. Instalação de Pacotes
- `apt install (nome do pacote)`: Este comando instala um pacote de software específico no sistema. Se o pacote já estiver instalado e uma nova versão estiver disponível, o comando também pode atualizar o pacote para a versão mais recente.

## 3. Busca de Pacotes
- `apt search (nome do pacote)`: Este comando busca pacotes de software nos repositórios com base em um nome ou palavra-chave fornecida. Ele retorna uma lista de pacotes que correspondem à consulta, junto com uma breve descrição de cada um.

## 4. Listagem de Pacotes
- `apt list`: Este comando lista pacotes de software de acordo com os critérios especificados. Ele pode listar todos os pacotes disponíveis, pacotes instalados, pacotes que têm atualizações disponíveis, entre outros.