# DIGISIGN - Digital Signature Transfer Project

Digital Signature is mathematical technique which is used to validate the authenticity of a file shared by a sender to one or many people.

Our project aims to encapsulate the method of creating signature certificates and sending it through the LAN to a receiving machine.

The receiver on the other side can also use this software to verify the signature.

## Requirements

- It requires the `Java Development Kit >= 1.8`;
Follow this [link](https://www.wikihow.com/Install-the-Java-Software-Development-Kit) for installation procedure.

- `Maven version >=3.0.0`. Follow this [link](https://maven.apache.org/download.cgi) for installation procedure.

After installing go inside the project folder.

Run `maven compile`

    - It will install the required jar files into a separate repository and will not disturb the java configuration of the machine.

Run  `mvn exec:exec -Dexec.executable="java" -Dexec.args="-classpath %classpath Login"`

    - This will execute the main Login class.

On executing, the Login Screen appears.
Rest is straightforward!
