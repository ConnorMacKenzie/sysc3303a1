package a1;

import java.io.*;
import java.net.*;

public class Server1 {

	DatagramPacket sendPacket, receivePacket;
	DatagramSocket sendSocket, receiveSocket;

	public Server1() {
		try {
			sendSocket = new DatagramSocket();
			receiveSocket = new DatagramSocket(1051);
		} catch (SocketException se) {
			se.printStackTrace();
			System.exit(1);
		}
	}

	public void sendAndReceive() {
		// receive from proxy

		// remove vowels
		// convert to bytes

		// send to proxy

		// close
		sendSocket.close();
		receiveSocket.close();
	}

	public static void main(String args[]) {
		for (int i = 0; i < 100; i++) {
			Server1 s = new Server1();
			s.sendAndReceive();
		}
	}
}
