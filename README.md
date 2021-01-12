# Main.cpp



#include 


// MaFenetre.cpp
 
#include "MaFenetre.h"
 
MaFenetre::MaFenetre() : QWidget()
{
    setFixedSize(230, 120);
 
    m_boutonDialogue = new QPushButton("Ouvrir la boîte de dialogue", this);
    m_boutonDialogue->move(40, 50);
 
    QObject::connect(m_boutonDialogue, SIGNAL(clicked()), this, SLOT(ouvrirDialogue()));
}
 
void MaFenetre::ouvrirDialogue()
{
    // Vous insérerez ici le code d'ouverture des boîtes de dialogue
}

