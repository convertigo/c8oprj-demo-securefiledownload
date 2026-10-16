
# ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/project_color_16x16.png?raw=true "Project") SecureFileDownloadDemo

Convertigo NGX builder Project

<details><summary><span style="color:DarkGoldenRod"><i>Connectors</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/connectors/images/sqlconnector_color_16x16.png?raw=true "SqlConnector") void

Placeholder SQL connector for template projects

<details><summary><span style="color:DarkGoldenRod"><i>Transactions</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/images/sqltransaction_color_16x16.png?raw=true "SqlTransaction") void

Placeholder transaction that intentionally cancels execution
</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Sequences</i></span></summary><blockquote><p>


<details><summary><b>DemoLogin</b> : DÉMONSTRATION UNIQUEMENT : authentifie le nom fourni sans mot de passe</summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/sequences/images/genericsequence_color_16x16.png?raw=true "GenericSequence") DemoLogin

DÉMONSTRATION UNIQUEMENT : authentifie le nom fourni sans mot de passe. À ne jamais utiliser en production.

<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;user
</td>
<td>
Aucun mot de passe : démonstration pédagogique uniquement.
</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>DemoLogout</b> : Déconnexion de la démonstration : retire l’utilisateur authentifié et termine la session HTTP</summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/sequences/images/genericsequence_color_16x16.png?raw=true "GenericSequence") DemoLogout

Déconnexion de la démonstration : retire l’utilisateur authentifié et termine la session HTTP.
</p></blockquote></details>

<details><summary><b>DemoSessionStatus</b> : Expose uniquement l’état booléen de la session de démonstration afin que l’interface puisse synchroniser ses contrôles</summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/sequences/images/genericsequence_color_16x16.png?raw=true "GenericSequence") DemoSessionStatus

Expose uniquement l’état booléen de la session de démonstration afin que l’interface puisse synchroniser ses contrôles.
</p></blockquote></details>

<details><summary><b>GetSecuredFile</b> : Sert un fichier du répertoire secured uniquement après vérification du contexte authentifié</summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/sequences/images/genericsequence_color_16x16.png?raw=true "GenericSequence") GetSecuredFile

Sert un fichier du répertoire secured uniquement après vérification du contexte authentifié.

<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;file
</td>
<td>
Le nom est validé par ResolveSecuredFile avant toute lecture.
</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>InstallDemoResources</b> : Initialise exclusivement les ressources statiques de la démonstration : </summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/sequences/images/genericsequence_color_16x16.png?raw=true "GenericSequence") InstallDemoResources

Initialise exclusivement les ressources statiques de la démonstration : .httpignore, secured/ et secure-demo.txt.
</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Mobile Application</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/mobileapplication_color_16x16.png?raw=true "MobileApplication") Application

Describes the mobile application global properties

<details><summary><span style="color:DarkGoldenRod"><i>Pages</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/pagecomponent_color_16x16.png?raw=true "PageComponent") Page

Default home page
</p></blockquote></details>
</p></blockquote></details>
