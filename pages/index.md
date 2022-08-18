---
layout: 'MyLayout'
blocks:
  # - name: CustomBlock
  - name: SectionBlock
    title: 'Hello World'
    description:
      - name: ContentIcon
        icon: i-mdi:code-tags
      - name: Alert
        content: Info
        title: 'Info'
        icon: i-mdi:apple
      - name: Alert
        content: Error
        type: error
      - name: Alert
        content: Warning
        type: warning
      - name: Alert
        content: Success
        type: success
  - name: SectionBlock
    title: 'This is a dark section'
    description: !md |
      A global leader in the financial sector has been working with ArcBlock to solve the challenges of managing and storing assets for the financial industry. The key was to design a smart asset system that doens't just record the asset in the supply chain, it’s serial numbers and value, but to also include other important and key data points such as where is it coming from and where is it going to; how does the asset relate to other assets in the overall supply chain; what is the components and component value of the asset; tax and government clearance information; and more.

      By leveraging blockchain technologies and ArcBlock's developer platform, we are enabling a new asset system that achieves these objectives and are able to store any required data on-chain on a single ledger. The data is verifiable, auditable and immutable helping to protect the value of the data and ensuring the partner is in compliance with any local, national or international laws.
    dark: true
    background:
      color: '#1A1723'
  - name: SectionBlockImage
    title: This page is written by Blocklet Page
    badge: BUILD.DEPLOY.RUN
    # description: !md |
    #   ArcBlock is your new **decentralized developer platform** that simplifies the development of **DApps, DLT and Blockchains**.
    # image:
    #   name: Screenshot
    #   type: phone
    #   src: ./imgs/screenshot.png
    actions:
      - name: Button
        children: LEARN HOW
        href: https://pages.blocklet.io/
        variant: contained
        color: primary
      - name: Button
        children: STRAT HOW
        href: https://pages.blocklet.io/
        variant: contained
        color: secondary
      - name: Button
        children: STRAT HOW
        href: https://pages.blocklet.io/
        variant: outlined
        color: secondary
      - name: Button
        children: STRAT HOW DID
        href: http://www.didconnect.io/
        variant: contained
        color: _did
      - name: Button
        children: STRAT HOW
        href: https://google.com
        variant: contained
        icon: i-mdi:google
        color: black
      - name: Button
        children: STRAT HOW
        href: https://apple.com
        variant: outlined
        icon: i-mdi:apple
        color: black
---

:::Alert{title=Notice}
This is a notice block
:::
