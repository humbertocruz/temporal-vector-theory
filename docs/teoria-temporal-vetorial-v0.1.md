# Teoria Temporal Vetorial v0.1

## Resumo

A Teoria Temporal Vetorial (TTV) propõe que o tempo seja modelado como um vetor tridimensional normalizado:

```math
\mathbf u_T=(u_\tau,u_\sigma,u_\rho),
\qquad
\|\mathbf u_T\|^2=1.
```

O componente `u_τ` representa o tempo próprio observável. Os componentes `u_σ` e `u_ρ` representam direções temporais ocultas. A velocidade espacial determina quanto da evolução total permanece projetada no tempo observável.

## Parametrização básica

```math
u_\tau=\sqrt{1-\frac{v^2}{c^2}}
```

```math
u_\sigma=\frac{v}{c}\cos\varphi
```

```math
u_\rho=\frac{v}{c}\sin\varphi
```

Assim:

```math
u_\tau^2+u_\sigma^2+u_\rho^2=1.
```

## Interpretação

Em repouso relativo:

```math
v=0 \Rightarrow \mathbf u_T=(1,0,0).
```

No limite luminoso:

```math
v\to c \Rightarrow u_\tau\to0,
```

com a evolução orientada integralmente no plano temporal oculto.

## Relação com energia e momento

Definindo um ângulo temporal `θ`:

```math
\sin\theta=\frac vc,
\qquad
\cos\theta=\sqrt{1-\frac{v^2}{c^2}},
```

obtemos:

```math
\gamma=\frac1{\cos\theta},
\qquad
\tan\theta=\gamma\frac vc.
```

Para uma partícula massiva:

```math
E=\frac{mc^2}{\cos\theta},
\qquad
p=mc\tan\theta.
```

Logo:

```math
mc^2=E\cos\theta,
\qquad
pc=E\sin\theta,
```

recuperando:

```math
E^2=m^2c^4+p^2c^2.
```

## Setores materiais

Hipóteses provisórias:

- matéria comum: orientação temporal alinhada ao setor observável;
- antimatéria: orientação oposta nas componentes temporais ocultas;
- matéria escura: orientação quase ortogonal ao setor eletromagnético observável;
- energia escura: possível efeito coletivo da geometria ou tensão do campo temporal oculto.

Essas associações ainda não constituem derivação física. São hipóteses de trabalho que precisam ser formalizadas por uma dinâmica de campos e confrontadas com dados.

## Condição de validade

A TTV deve:

1. reproduzir os resultados confirmados da relatividade especial;
2. admitir extensão covariante compatível com gravitação;
3. evitar graus de liberdade instáveis ou energias negativas não controladas;
4. gerar ao menos uma previsão diferente das teorias existentes;
5. permitir falsificação experimental.
