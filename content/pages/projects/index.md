---
type: ProjectFeedLayout
title: Projetos
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/mathias-reding-ZHqCrllTaeM-unsplash.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 50
projectFeed:
  type: ProjectFeedSection
  colors: colors-f
  showDate: false
  showDescription: true
  showReadMoreLink: true
  showFeaturedImage: true
  variant: variant-a
  styles:
    self:
      width: narrow
      padding:
        - pt-0
        - pl-4
        - pr-4
        - pb-12
styles:
  title:
    textAlign: left
bottomSections:
  - type: ContactSection
    backgroundSize: full
    title: "Vamos falar... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: Primeiro Nome
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Último Nome
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Conte-me sobre o seu projeto
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Subscreva para receber a minha resposta
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Enviar \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
