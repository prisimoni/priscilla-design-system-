# priscilla-design-system-
Priscilla Simoni · SEO &amp; GEO Engineering
/* ====================================================
   PRISCILLA SIMONI · DESIGN SYSTEM v1.0
   SEO & GEO Engineering
   ==================================================== */

:root {
  /* CORES PRIMÁRIAS */
  --white: #FFFFFF;
  --bg-soft: #FBF7F8;
  --ink: #1F1A24;
  --muted: #7C7385;

  /* CORES DA MARCA */
  --lilac: #9D7FFE;
  --lilac-deep: #5B3FCC;
  --lilac-soft: #E8E0FF;

  /* CORES DE ACENTO */
  --rose-burnt: #C5536A;
  --rose-soft: #F0D9DE;

  /* GRADIENTES */
  --grad-brand: linear-gradient(135deg, var(--lilac), var(--rose-burnt));
  --grad-soft: linear-gradient(155deg, var(--lilac-soft), var(--rose-soft));

  /* TIPOGRAFIA */
  --font-display: 'Plus Jakarta Sans', sans-serif;
  --font-mono: 'JetBrains Mono', monospace;

  /* PESOS */
  --weight-regular: 400;
  --weight-medium: 500;
  --weight-semibold: 600;
  --weight-bold: 700;
  --weight-extra: 800;

  /* TAMANHOS — escala desktop */
  --text-xs: 11px;
  --text-sm: 13px;
  --text-base: 15px;
  --text-lg: 18px;
  --text-xl: 24px;
  --text-2xl: 32px;
  --text-3xl: 42px;
  --text-4xl: 64px;
  --text-display: 120px;

  /* TRACKING */
  --tracking-tight: -2px;
  --tracking-normal: -0.5px;
  --tracking-wide: 1.5px;
  --tracking-mono: 2px;

  /* RAIOS */
  --radius-sm: 12px;
  --radius-md: 16px;
  --radius-lg: 20px;
  --radius-xl: 24px;
  --radius-pill: 30px;
  --radius-circle: 50%;

  /* ESPAÇAMENTO */
  --space-1: 4px;
  --space-2: 8px;
  --space-3: 12px;
  --space-4: 16px;
  --space-6: 24px;
  --space-8: 32px;
  --space-10: 40px;
  --space-12: 48px;

  /* BORDAS */
  --border-soft: 1px solid #EFE9EB;
  --border-dashed: 1px dashed #D9CFD3;
}

/* COMPONENTES */
.pill-rose {
  display: inline-flex;
  align-items: center;
  gap: var(--space-2);
  padding: var(--space-2) var(--space-3);
  background: var(--rose-soft);
  color: var(--rose-burnt);
  border-radius: var(--radius-pill);
  font-family: var(--font-mono);
  font-size: var(--text-xs);
  letter-spacing: var(--tracking-wide);
  font-weight: var(--weight-semibold);
}

.pill-lilac {
  background: var(--lilac-soft);
  color: var(--lilac-deep);
}

.headline-display {
  font-family: var(--font-display);
  font-size: var(--text-3xl);
  font-weight: var(--weight-extra);
  letter-spacing: var(--tracking-tight);
  line-height: 1;
}

.cta-button {
  background: var(--lilac);
  color: var(--white);
  padding: 14px 24px;
  border-radius: var(--radius-pill);
  font-weight: var(--weight-bold);
  font-size: var(--text-sm);
}

/* FORMATO DE POSTS INSTAGRAM */
.post-frame {
  aspect-ratio: 4/5;
  width: 1080px;
  height: 1350px;
}

.post-padding {
  padding: var(--space-10);
}
