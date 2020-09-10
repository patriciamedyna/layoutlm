# layoutlm

Trata-se de Notebook que executa o códido do artigo LayoutLM: Pre-training of Text and Layout for Document Image Understanding. Github: https://github.com/microsoft/unilm/tree/master/layoutlm

Seguindo as instruções disponíveis no github do artigo para executar o código, observaram-se incompatibilidades com a versão pytorch==1.4.0 (conda install pytorch==1.4.0 cudatoolkit=10.1 -c pytorch). Desse modo, utilizou-se a versão torch==1.5.0 (!pip install torch==1.5.0+cu101 torchvision==0.6.0+cu101 -f https://download.pytorch.org/whl/torch_stable.html)
